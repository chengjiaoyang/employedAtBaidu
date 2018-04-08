# 1 上来就是几个没听说过的名词
## mod.JS  对比 require.js
modJS是百度fex-team提供的一个轻量级的模块加载器，类似requirejs。
但modJS并不完全兼容规范amd/cmd，事实上，只支持非常简单的全局方法define(id,factory)。
另外factory提供了3个参数require/exports/module，用于引用和导出模块。



## yog2 



## swig 对比 ejs  jade



## bigpipe   BigPipe 是FaceBook 在性能优化探索的过程中结合自己的业务场景提出来的一个优化手段，
并在FaceBook中取得了巨大的成就,在2009年的时候，他们使用BigPipe和其它一些优化手段，成功将网站的响应速度提高了到之前的两倍
Facebook 的 BigPipe 技术，是通过将站点分解为多个 pagelet 小块，每个pagelet 获取数据与渲染均是独立的，
当传统的后端模板渲染模式受限于后端响应速度最慢的接口时，BigPipe 模式可以实现 pagelet 的数据一旦返回，
就可以无阻塞的在浏览器端进行渲染，以此来实现大型复杂页面的性能加速。

## Quickling 实现局部刷新
除了 BigPipe 模式外，我们还可以将 pagelet 用于 Quickling 模式。所谓 Quickling 模式是将 widget 整体通过 Ajax 请求返回。
也就是将传统的 Ajax 请求数据，前端模板渲染数据的模式变化为 Ajax 请求渲染好的页面以及 widget 执行的必要代码和样式。
这两种方式并非互相取代的关系，而是应该根据使用场景灵活判断。

# 2 几个名词解释 
widget ：前端组件（包含分页，轮播，弹框等，每个widget可以包含tpl，less， js文件）      ```要求每个组件写js逻辑```
swig:前端模板引擎,语法简练高效
router：node路由，处理url路径
bigpipe：无阻塞的在浏览器端进行渲染，以此来实现大型复杂页面的性能加速

项目涉及到 
Swig／Node.js／Nodejs／less／git／linux 

＃2安装虚拟机和LNMP学习一下php
##下载的VMware的的装好虚拟机ubuntu安装
