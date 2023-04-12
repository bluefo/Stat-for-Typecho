# Stat-for-Typecho
Stat Plugin for Typecho to Count Page Views
Stat 文章浏览计数器插件


修复了在 Typecho 1.2 版本中不能正常更新的问题。

插件使用方法：
上传到usr/plugins/stat/plugins.php 后，在管理后台启用即可。
在需要输出的地方（比如模板的post.php中）插入`<?php $this->views(); ?>次浏览`的代码即可。


