mxgraph-zheta
=======

模块化mxgraph(基于版本v3.6.0).全局变量mx.

使用方法:
```shell
npm install mxgraph-zheta --save
```

然后:
```js
var mx = require('mxgraph-zheta');
```

采用script方式加载.
```html
<script src="./mxgraph-zheta"></script>
```
然后:
```js
// 注入全局变量mx
var graph = new mx.mxGraph(container);
```

全局配置变量:

The following global variables may be defined before the client is loaded to
  specify its language or base path, respectively.
  
  - mxBasePath: Specifies the path in <mxClient.basePath>.
  - mxImageBasePath: Specifies the path in <mxClient.imageBasePath>.
  - mxLanguage: Specifies the language for resources in <mxClient.language>.
  - mxDefaultLanguage: Specifies the default language in <mxClient.defaultLanguage>.
  - mxLoadResources: Specifies if any resources should be loaded. Default is true.
  - mxLoadStylesheets: Specifies if any stylesheets should be loaded. Default is true.


mxGraph is a fully client side JavaScript diagramming library that uses SVG and HTML for rendering. It is the underlying technology that powers the drawing functionality that you see in [draw.io](https://www.draw.io). The [sources to draw.io](https://github.com/jgraph/draw.io) are also available.

mxGraph supports IE 9+, Chrome 30+, Firefox 31+, Safari versions actively patched by Apple (6.2.x, 7.1.x, 8.0.x and 9.x at time of writing), Opera 20+, Native Android browser 5.x+, the default browser in the current and previous major iOS versions (e.g. 9.x and 8.x) and Edge 20+.

mxGraph uses no third-party software, it requires no plugins and can be integrated in virtually any framework. Also provided is server-side functionality in Java and .NET for persistence (open and save) functionality, as well as server-side image generation.

Getting Started
===============

In the root folder there is an index.html file that contains links to all resources. You can view the documentation online on the [Github pages branch](https://jgraph.github.io/mxgraph/). The key resources are the JavaScript user manual, the JavaScript examples and the JavaScript API specificiation.

Support
=======

There is a [mxgraph tag on Stack Overflow](http://stackoverflow.com/questions/tagged/mxgraph) that we try to keep answered. Please ensure your questions adhere to the [SO guidelines](http://stackoverflow.com/help/on-topic), otherwise it will be closed.
