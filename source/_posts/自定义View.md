---
title: 自定义View
date: 2017-11-28 16:01:23
tags:
author: mushanYun
---

### “我是个俗气至顶的人，见山是山，见海是海，见花便是花。唯独见了你，云海开始翻涌，江潮开始澎湃，昆虫的小触须挠着全世界的痒。你无需开口，我和天地万物便通通奔向你。"



<!--more-->

### 关于自定义view的一些记录. 

```	
看网上的博客,每一次都会有一点收获,但收获总归是收获,不是自己的,所以就打算把这些收获整理一下,防止记忆力衰退的我以后再想不起来
```

​	

# LayoutInflater 

* LayoutInflater的基本用法  加载布局使用

  ```
  //创建View的方式,
  LayoutInflater.from(this),其实内部还是调用context.getSystemService(Context.LAYOUT_INFLATER_SERVICE);

  View view = LayoutInflater.from(this).inflate(R.layout.custom_layout, null);
  ```