# sidenav 

一个可折叠的侧边栏插件。可以把自己常用的网页，以iframe的形式收纳在侧边栏里。而且，本插件还优化了网络性能，即使加载多个iframe，也不会影响网页的加载速度。

## 效果演示

[Demo](https://luochang212.github.io/demo/sidenav/)

## 特性

- 即使在加载多个iframe的情况下，也不会影响网页的加载速度

- 关闭侧边栏之后，音乐播放器依旧可以正常工作

## 用法

将下面的`&#9776; open`替换为你网页中的元素

```
<a href="#" class="load-iframe" onclick="openNav()" style="font-size:30px;cursor:pointer">&#9776; open</a>
```