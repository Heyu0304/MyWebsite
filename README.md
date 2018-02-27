# MyWebsite
以此来记录我建站的过程和所遇到的困难吧。
===
+ 个人感觉大部分技术不难，难的是没有目标，不知道自己想要什么样子，个人理解就是懒
+ 没有思想的灵魂最为可怕
在此写下这篇文章，来记录自己的心路过程，也给自己敲下一个警钟。<br>
        顺便写一下自己说用到的技术
        React+webpack+react-router+antd
## 首先遇到的困难吧
        图片的导入部分，在webpack中，如果你想插入一张本地图片，在<img url="">直接插入地址是没有效果的<br>
        需要用require来倒入 const logo = require("../img/logo.jpg");
