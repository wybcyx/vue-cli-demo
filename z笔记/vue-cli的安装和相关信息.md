vue.js 著名的全家桶系列, 包含了， vue-router, vuex， axios，再加上 vue-cli 
就是一个从 路由，数据流管理，http请求都有的核心项目，vue 社区的丰富资源，也是满足了我们日常开发中的需求了。

在使用vue-cli之前，请确认你的电脑已经安装了 node，建议版本在 8.0.0 以上
在国内使用npm有些资源会比较慢，可以使用cnpm
（npm install -g cnpm --registry=http://registry.npm.taobao.org ）

使用 npm全局安装 webpack，打开命令行工具输入：
npm install webpack -g

安装完成之后输入：
webpack -v
如果出现相应的版本号，则说明安装成功。
(注意：webpack 4.X 开始，需要安装 webpack-cli 依赖 ,所以使用这条命令：
npm install webpack webpack-cli -g)

全局安装 vue-cli
在命令行中输入：
npm install -g vue-cli
安装完成后，检验是否安装成功，输入 ：
vue -V (注意：这里是大写的 “V”)
如果出现版本号，则说明安装成功。

用 vue-cli 来构建项目
vue init webpack project-name

安装完成后，安装提示，cd 到项目目录, 执行命令 npm install 进行初始化。