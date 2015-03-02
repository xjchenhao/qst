# qst(Quick Styling Toolkit)

##什么是Q.S.T
1. qst 是一个基于 [Stylus](http://learnboost.github.io/stylus/) 的样式工具库，帮助您更轻松地书写 Stylus 代码。
2. qst 提供了一系列方便快捷的 mixin，只在调用时才输出代码。qst 不希望提供直接给 HTML 调用的类名，用「样式类」污染 HTML 代码的语义。当然您也可以根据自己的项目需求基于 qst 搭建样式类库，提供类名接口来进行快速开发。
3. 仿照[百度EFE团队](http://efe.baidu.com/)的基于LESS写的[est样式工具库](http://ecomfe.github.io/est/)，目录结构和提供的接口与之基本保持一致。

##功能概述
* 初始化页面
* px-rem单位转换
* 免浏览器兼容的前缀
* 无需写css hack
* 文本浮凸、凹陷、3d等效果
* 封装文本溢出省略号、画小三角等常用代码

##快速开始
1. 下载最新版qst

    [https://github.com/xjchenhao/qst/releases](https://github.com/xjchenhao/qst/releases)
2. 在.styl文件中引入、配置

    ```
    // 引入qst
    @import 'qst/all';

    // 设置基础变量
    $default-font-size = 17.777778px
    $default-border-radius = 5px;
    $default-base-font-family = "Helvetica Neue", Helvetica, STHeiTi, sans-serif
    $original-size = false;

    // 下面写你自己的代码
    ……
    ```

##功能模块
* [variables](https://github.com/xjchenhao/qst/wiki/variables)
* [normalize](https://github.com/xjchenhao/qst/wiki/normalize)
* [reset](https://github.com/xjchenhao/qst/wiki/reset)
* [compatibility](https://github.com/xjchenhao/qst/wiki/compatibility)
* [util](https://github.com/xjchenhao/qst/wiki/util)
* [typography](https://github.com/xjchenhao/qst/wiki/typography)
* [effects](https://github.com/xjchenhao/qst/wiki/effects)
* [shapes](https://github.com/xjchenhao/qst/wiki/shapes)
* [oocss](https://github.com/xjchenhao/qst/wiki/oocss)
* [adaptive](https://github.com/xjchenhao/qst/wiki/adaptive)

##更多资料
* [stylus中文文档](http://www.zhangxinxu.com/jq/stylus/)
* [stylus英文文档](http://learnboost.github.io/stylus/)