# koa-auto-routes

> a tool to auto map your routers folder and router for koa

## 用法

#### 安装

```shell
    npm install koa-auto-routes --save
```

#### 引入

在koa工程目录下的入口文件里

```js
    var autoRoutes=require('koa-auto-routes')
    
    autoRoutes(app,'routes目录路径')
```

然后，koa-auto-routes就会自动帮你生成路由 ^.^

注意:index.js对应默认路径'/'

[简单demo](https://github.com/flypie2/koa-auto-routes-demo)

### dependence:

node.js V4+