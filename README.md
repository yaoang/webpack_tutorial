# Webpack Tutorial Webpack配置教程
> Author: yaoang  

　　我们开发react等前端项目，经常需要使用到webpack来进行编译，所以掌握webpack基本的配置方法还是非常必要的。  
　　我们先看看一个简单的配置例子。


```javascript
const path = require('path');  
const webpack = require('webpack');  
const ExtractTextPlugin = require('extract-text-webpack-plugin');      
```

我们需要引入基本的node库，其中：
- path:用于处理“目录”先关的操作  
- webpack: 我们的主角  
- ExtractTextPlugin: 用于把某些特别类型的格式输出成**独立**的文件，比如**scss**
  

  




