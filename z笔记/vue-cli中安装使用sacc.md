#创建项目
1、打开项目终端，安装sass依赖文件
npm insatll sass-loader --save-dev
npm intsall node-sass --save-dev         // sass使用需要依赖于node-sass

2、找到vue文件夹下的webpack.base.conf.js文件
找到下面这一行代码
此代码后面添加下面配置

 {       
        test: /\.sass$/,        
        loaders: ['style', 'css', 'sass']    
  } 
3、修改style属性值

4、最后运行项目
终端输入  ： npm run dev

5、如果显示报错



这是因为当前sass的版本太高，webpack编译时出现了错误，这个时候只需要换成低版本的就行，下面说一下修改方法，很简单，如下，找到package.json文件，里面的 "sass-loader"的版本更换掉 就行了。

6、卸载sass-loader
npm uninstall sass-loader --save-dev

7、下载低版本sass-loader
npm install sass-loader@7.3.1  --save-dev

8、重新关闭项目，重新运行
npm run dev

9、项目正常启动
