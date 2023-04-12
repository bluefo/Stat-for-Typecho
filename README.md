# Stat-for-Typecho
Stat Plugin for Typecho to Count Page Views

修复了在 Typecho 1.2 版本中不能正常更新的问题。

使用方法：
上传到usr/plugins/stat/plugins.php 后在后台启用即可。
在需要输出的地方（比如模板的post.php中）插入`<?php $this->views(); ?>次浏览`的代码即可。


