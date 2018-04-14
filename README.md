# 微信小程序--起重圈
### 项目下载 
tab 推荐使用 git clone url 或 Down Load

### 安装依赖
tab npm i/install && cnpm i/install

### 生成小程序目录
tab 1.npm install wepy-cli -g  全局安装wepy脚手架
    2.根目录 dos命令输入 wepy build --watch
    3.根目录生成 dist文件

### 浏览小程序
tab 1.下载微信开发者工具 并通过微信开发者工具以dist为根目录打开项目
    2.微信开发者工具---->详情----->es6: 对应关闭ES6转ES5选项，关闭。 重要：未关闭会运行报错。

    postcss: 对应关闭上传代码时样式自动补全选项，关闭。 重要：某些情况下漏掉此项也会运行报错。

    minified: 对应关闭代码压缩上传选项，关闭。重要：开启后，会导致真机computed, props.sync 等等属性失效。（注：压缩功能可使用WePY提供的build指令代替，详见后文相关介绍以及Demo项目根目录中的wepy.config.js和package.json文件。）

    urlCheck: 对应不检查安全域名选项，开启。 如果已配置好安全域名则建议关闭。

