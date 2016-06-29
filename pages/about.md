---
layout: page
title: About
description: 打码改变世界
keywords: Wen Qin, 阿文
comments: true
menu: 关于
permalink: /about/
---

眼中有码,心中也有码.

## 坚信

* 熟能生巧
* 努力改变人生

## 联系

* GitHub：[@mzlogin](https://github.com/alvingeek)
* 博客：[{{ site.title }}]({{ site.url }})

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Mobile Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_mobile_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Windows Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_windows_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
