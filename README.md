### 手写实现一个迷你的Vite——miniVite
所以，笔者怀着一颗敬畏的心，在参考了一些教程之后，尝试自己实现一下当下火热的**vite**，通过这种方式来加深对这些bundless工具的理解。

### 思路
* 利用koa，启一个http server
* 利用babel，将所有的import路径改为`/`、`./`、`../`这三种路径方式
* 编译.vue文件，返回对应的html、js、css文件
* 添加预编译功能，对依赖库文件进行强缓存，对我们编写的代码进行协商缓存
* 。。。规划中

### 启动
* yarn i：安装依赖
* yarn dev：利用nodemon启动koa服务
* 利用nodemon启动 nodemon kvite.js
