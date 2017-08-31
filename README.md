# React-xiaoshu
胡子大哈的React小书的代码


1.使用create-react-app来快速搭建开发环境

2.	create-react-app创建的目录隐藏了一些打包的信息，运行以下命令就可以看到隐藏的文件,即webpack相关的配置信息
npm run eject

3.	create-react-app创建的项目启动之后默认的端口是3000，因为自己本地的项目已经占用3000端口，想要修改端口为自己设置的，找到scripts目录下面的start.js文件，搜索DEFAULT_PORT这个变量，将其默认值改为自己期望值就可以。
