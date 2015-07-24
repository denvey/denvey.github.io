title: "table-border-bug"
date: 2015-07-24 17:53:06
tags:
---

table中td设置了overflow:hidden,在ios中的safari会出现不能设置border-top,border-bottom的情况
{% qnimg table_border_bug/table_border_bug_1.PNG title:图片标题 extend:?imageView2/0/w/700 %}

不设置overflow:hidden,border就可以控制了
{% qnimg table_border_bug/table_border_bug_2.PNG title:图片标题 extend:?imageView2/0/w/700 %}