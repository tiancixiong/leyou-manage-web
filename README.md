# leyou-manage-web

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

# 启动说明
1.通过`npm install`安装依赖
2.通过`npm run dev`启动
如果启动报错：
```
Module build failed: Error:

Vue packages version mismatch:

- vue@2.6.10
- vue-template-compiler@2.5.16
```
先执行下面命令：
```
npm install vue@2.5.2 --save
npm install vue-template-compiler@2.5.2 --save
```
执行成功后再通过`npm run dev`启动项目
