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

热爱IT,向高级码农奋斗中！

## 座右铭

* 要有追求,懂得为追求而上进。
* 男人就该对自己好一点。

## 联系

* GitHub: [@DoctorDeng](https://github.com/DoctorDeng)
* 慕  课  网: [@MotoDoctor](http://www.imooc.com/u/2400213)
* 实  验  楼: [@MotoDoctor](https://www.shiyanlou.com/user/125214)
* 简        书: [@Doctor邓](http://www.jianshu.com/users/ba7ec0a7438e/timeline)

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