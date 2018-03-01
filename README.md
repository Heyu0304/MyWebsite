# MyWebsite
以此来记录我建站的过程和所遇到的困难吧。
===
+ 个人感觉大部分技术不难，难的是没有目标，不知道自己想要什么样子，个人理解就是懒
+ 没有思想的灵魂最为可怕
在此写下这篇文章，来记录自己的心路过程，也给自己敲下一个警钟。<br>
        顺便写一下自己说用到的技术
        React+webpack+react-router+antd
## 首先遇到的困难吧
# 一：webpack
        图片的导入部分，在webpack中，如果你想插入一张本地图片，在<img url="">直接插入地址是没有效果的<br>
        需要用require来倒入 const logo = require("../img/logo.jpg");
# 二：CSS
+ 布局方面，我仿照的是 https://segmentfault.com/a/1190000011399153 这位的教程。用的是flex布局。<br>
  在此，还是把阮大神的网站直接拿来吧。http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html?^%$ <br>
  如果只有一个模块，想把设置居中的话，在父组件设置： <br>
        justify-content:center; <br>
        align-items: center;    <br>
+ 如果背景图片过大，可以用这个网站来压缩一下 https://tinypng.com/
+ 关于背景图片自适应的问题，一个人设计网站的麻烦还要自己处理图片。 我是参照这个网站的，很简单的解决了
  如果图片是固定大小的话
  background-repeat:no-repeat; background-size:100% 100%;-moz-background-size:100% 100%;
http://blog.csdn.net/chenqk_123/article/details/44402355
 
 # 三：Github 
 + 最近遇到了一些麻烦，很是纠结，关于Github 上边的api接口，已经升级为V4版本，但是网上关于V4的介绍还是少了点。<br>
 前后端交互的问题还是没有遇到过，如果我用V3版本应该导出来没问题。还是慢慢摸索。
        
