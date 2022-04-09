# mini-vite
手写简易版vite实现


### 思路
* 利用koa，启一个http server
* 利用babel，将所有的import路径改为`/`、`./`、`../`这三种路径方式
* 编译.vue文件，返回对应的html、js、css文件
* 添加预编译功能，对依赖库文件进行强缓存，对我们编写的代码进行协商缓存
* 规划中


### 启动
* yarn i：安装依赖
* yarn dev：利用nodemon启动koa服务
* 利用nodemon启动 nodemon kvite.js
