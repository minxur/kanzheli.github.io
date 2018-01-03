---
layout: archive	 
title: "信息可视化"
date: 20181-03T11:40:45-04:00
modified:
excerpt:"我的信息可视化作品&笔记"
tags: []
image: 
	feature: base.jpg
	teaser:base.jpg
---
<div class="tiles">

{% for post in site.categories.infovis %}
	{% include post-grid.html %}
{% endfor %}
</div>