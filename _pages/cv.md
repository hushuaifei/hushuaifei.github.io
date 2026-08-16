---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======
* 计算数学博士，上海师范大学，2023--2026
  * 导师：焦裕建
* 数学硕士，温州大学，2020--2023
  * 导师：安荣
* 数学与应用数学学士，安阳师范学院，2015--2019

工作经历
======
* 2026年8月至今：数学教师
  * 平顶山学院
  * 主要从事数学教学与科研工作

研究方向
======
* 偏微分方程数值解
* 有限差分方法
* 有限元方法
* 谱方法
* 数值分析与科学计算

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% comment %}
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
{% endcomment %}
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
