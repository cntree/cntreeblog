title: selenium打开firefox后总是要进行导入设置
date: 2015-08-21 15:23:32
tags: selenium
---

解决方案

``` bash
#修改profiles.ini文件
将IsRelative=1改为IsRelative=0 
```
profiles.ini文件位于“C:\Users\~\AppData\Roaming\Mozilla\Firefox”目录下