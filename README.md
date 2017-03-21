# Webpack Tutorial Webpack配置教程
> Author: yaoang  

　　我们开发react等前端项目，经常需要使用到webpack来进行编译，所以掌握webpack基本的配置方法还是非常必要的。  
　　我们先看看一个简单的配置例子。

1. 第一步，现在项目的根目录下，创建一个空文件，**webpack.config.js**  
2. 开始一步步编写配置


```javascript
const path = require('path');  
const webpack = require('webpack');  
const ExtractTextPlugin = require('extract-text-webpack-plugin');      
```

我们需要引入基本的node库，其中：
- path:用于处理“目录”相关的操作，基本每一个webpack的配置文件都会用到它  
- webpack: 我们的主角，必备  
- ExtractTextPlugin: 插件，用于把某些特别类型的格式输出成**独立**的文件，比如**scss**，非必要项，不过建议使用。


  




