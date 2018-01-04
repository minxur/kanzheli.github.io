---
layout: archive
title: "信息可视化笔记"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "记录了信息可视化的基本知识和分享一些个人经验。另外添加了一些有关的网站。"
tags: []
image: 
  feature: base.jpg
  teaser: base.jpg
---


<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>
