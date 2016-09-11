---
layout: page
title: About
description: 书是个好东西哈
keywords: DoctorDeng, 邓华杰
comments: true
menu: 关于
permalink: /about/
---

我是邓华杰，自称Doctor邓。

漫天星海中,我是一颗不起眼的星,但我也能发亮啊！

## 座右铭

* 要有追求,懂得为追求而上进。
* 男人就该对自己好一点。

## 联系

* GitHub：[@DoctorDeng](https://github.com/DoctorDeng)
* 慕课网：[@MotoDoctor](http://www.imooc.com/u/2400213)
* 实验楼: [@MotoDoctor](https://www.shiyanlou.com/user/125214)
* 简书:[@Doctor邓](http://www.jianshu.com/users/ba7ec0a7438e/timeline)

## 职业技能

#### 后端
<div class="btn-inline">
    {% for keyword in site.skill_server_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### 前端
<div class="btn-inline">
    {% for keyword in site.skill_web_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### 了解
<div class="btn-inline">
    {% for keyword in site.skill_know_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>