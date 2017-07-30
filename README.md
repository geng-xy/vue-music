# vue-music

> music

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

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## music项目创建记录
  ### 初始化操作
     - 安装脚手架工具 npm i vue-cli -g;
     - 初始化vue项目 vue init webpack vue-music
     - 安装项目依赖 npm install
  ### 基本文件操作
     - 安装stylus和stylus-loader 并加进package.json的依赖中
     - 为eslintrc.js文件添加es6语法设置
      +  'eol-last': 0//不检测文件末尾是否有空行
      +   'space-before-function-paren': 0 //左括号前面不加空格
     - webpack.base.conf.js里添加别名
      + 添加以后需要再npm install --save 保存依赖
     - 清除assets等不需要的文件
