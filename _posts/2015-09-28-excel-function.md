---
layout: post
category : Operation
tagline: "excel技巧"
tags : [tools]
title:  "Excel 常用函数技巧"
comments: true
---

###判断单元格是否含有该字符，结合筛选

	=IF(ISERROR(FIND("9",B5)),"不包含","包含")

![img](http://7xkqbu.com1.z0.glb.clouddn.com/iserror+find.jpg)

