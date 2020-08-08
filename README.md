# 简介
* 原脚本地址：https://greasyfork.org/zh-CN/scripts/383636
* 因觉得原脚本字体的萍方粗体过于粗大，于是自己改为了较细的萍方常规。<br/>
* 只能渲染网页字体，而浏览器本身的菜单等设置项不支持。<br/>
* 使用油猴脚本调用系统字体强制渲染网页字体，所以需先安装字体。<br/>
# 说明
由于Chrome及新版Edge浏览器均不支持DirectWrite、mactype字体渲染，于是使用脚本强制渲染。我尝试在浏览器外观设置中更换了很多字体，大多发虚模糊，而**思源黑体**效果较好，但在启用脚本后强制渲染为**萍方常规**更有质感且滚动更平滑。<br/>
也尝试将脚本中**萍方常规**换为**思源黑体**，仍不尽人意，只有**萍方**系列字体在此脚本中效果良好，而**萍方常规**大小正合适。~~纯代码小白，只会换字体。~~**注意此脚本会造成部分网页的图标显示不完全，若出现此情况需暂时关闭此脚本然后刷新网页。**<br/>
于是采用此方案：
> 浏览器字体使用思源黑体，网页字体使用脚本强制渲染为萍方常规。
# 安装
* 先下载字体安装：https://cdn.jsdelivr.net/gh/ChirmyRam/SmoothScroll@latest/PingFang-SC-Regular.ttf
* 再点击安装脚本：https://cdn.jsdelivr.net/gh/ChirmyRam/SmoothScroll@latest/SmoothScroll.user.js
# 效果
![启用脚本前](https://cdn.jsdelivr.net/gh/ChirmyRam/SmoothScroll@latest/before.jpg)
![启用脚本后](https://cdn.jsdelivr.net/gh/ChirmyRam/SmoothScroll@latest/after.jpg)
