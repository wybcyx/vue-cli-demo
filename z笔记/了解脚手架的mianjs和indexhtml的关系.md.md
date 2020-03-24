初始化的vue-cli中，存在main.js和index.html、App.vue

1、mian.js被称为入口文件，文件中通过new Vue创建vue实例化，
我们可以把main.js理解成是index.html页面中的js文件，此时new Vue()中的el绑定的则是index.html中的#app，所以这个new Vue()是对index.html页面的实例，接着在实例中注册了App.vue组件，通过template挂载到了index.html中的#app里，完全覆盖掉了index.html中的内容，大家可以改变App.vue中的#app试试，运行页面后看到的就是App.vue中的id