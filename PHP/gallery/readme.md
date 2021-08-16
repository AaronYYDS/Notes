这是一款简洁漂亮的目录程序：files.photo.gallery，直接上传index.php即可使用。



- 效果演示：https://files.photo.gallery/demo

- 设置说明：https://forum.photo.gallery/viewtopic.php?f=66&t=9964

## 下载及安装：

官方下载：https://cdn.jsdelivr.net/npm/files.photo.gallery/index.php

我的修改版本：https://github.com/AaronYYDS/Notes/blob/main/PHP/gallery/index.php

PHP需要安装GD、mbstring、fileinfo和exif扩展，安装完毕后记得重启PHP。

## 破解授权：

有能力的请支持一下作者。正版授权和破解无任何区别，只是把授权验证代码给去掉了。

```
破解方法：打开index.php，在最后面找到：
<script src="<?php echo config::$assets ?>js/files.js"></script>
把它修改为： 
<script src="https://cdn.jsdelivr.net/gh/AaronYYDS/Notes/JS/files.js"></script>
保存即可。
```
![gallery](https://cdn.jsdelivr.net/gh/AaronYYDS/Notes/IMG/gallery.png)