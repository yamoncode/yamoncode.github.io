---
title: PostgreSQL函数-unnest
description: PostgreSQL函数-unnest函数的简单使用
date: 2025-05-12 11:33:00 +0800
categories: [Blogging]
tags: [PostgreSQL]
pin: true
math: true
mermaid: true
typora-root-url: ../../yamoncode.github.io/
---

# unnest函数
官方文档对于该函数的说明

![image-20250514150250129](/assets/blog_res/2025-05-14-postgresql-unnset函数.assets/image-20250514150250129.png)

示例：
现在表里有以下数据

![image-20250514151040209](/assets/blog_res/2025-05-14-postgresql-unnset函数.assets/image-20250514151040209.png)

使用unnest函数

![image-20250514151122185](/assets/blog_res/2025-05-14-postgresql-unnset函数.assets/image-20250514151122185.png)

有时，在遇到表里面像newtable那样的数据，又要求能根据单个brand去查询某个值，可以使用unnest函数。
