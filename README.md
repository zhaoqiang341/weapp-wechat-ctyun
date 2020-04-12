# 微信小程序源码结构：

 *视图层（将逻辑层的数据展现在视图上）
 
 *逻辑层（通过改变数据[setData方法]来改变视图）
 
#配置文件

 *在小程序中，微信规定了界面的组成模式，由四个文件组成：
 *wxml 文件（页面结构文件）标签语言，类似 HTML，真正负责页面结构的文件，可以绑定数据；
 *wxss 文件（样式表文件）类似 CSS，大部分 CSS 样式都相同；
 *js 文件（脚本文件）用来运行我们的逻辑，使用 JS 语言；
 *json 文件（配置文件）主要配置公用的样式，比如 Tab 栏、窗口样式等。
