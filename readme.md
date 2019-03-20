> 此项目是我学习webpack官方文档时候的git仓库
> 因此，此处用于记录一些比较关键的笔记



## 1. HMR 与 webpack-dev-server

> https://www.webpackjs.com/guides/development/#%E4%BD%BF%E7%94%A8-webpack-dev-server
> 在学习到此处的时候发现已经可以一更改代码就刷新页面，不用手动刷新页面
> 当看到 https://www.webpackjs.com/guides/hot-module-replacement/ 模块热替换的时候就不懂了，没啥区别啊

### 问题 与 答案
其实区别在于配置好了Hot之后，页面就完全不用刷新就能更改页面了，最直观的是console.log的历史记录不会被清空啊