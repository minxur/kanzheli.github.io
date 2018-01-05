---
layout: archive
title: "信息可视化"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature: base.jpg
  teaser: base.jpg
---
<div class='tableauPlaceholder' id='viz1515164254814' style='position: relative'>
	<noscript><a href='#'><img alt='信息可视化：关于师徒四人的故事 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;xi&#47;xiyou&#47;sheet4&#47;1_rss.png' style='border: none' /></a>
	</noscript>
	<object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='xiyou&#47;sheet4' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;xi&#47;xiyou&#47;sheet4&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' />
	</object>
</div>                
<script type='text/javascript'>                    var divElement = document.getElementById('viz1515164254814');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

##### 分布地图
- 此图可以看出，关于几个关键词，分布都集中在东南沿海地区，东南沿海是中国经济较为发达的地区，因此可以推断分布的位置跟经济发展有关。
- 很容易看出，在图中绿色图标（即关键词“八戒”）最多，而且也有涉及到中国的西部和北部。或许“八戒”这个角色在西游记中比较深入人心。
- 观察发现，悟空和八戒两位角色在中国新疆、西藏、内蒙古等地区的知名度比其它两位要高，应用的频率虽然不高(可能是因为经济发展程度的关系)，但也有一定数量。
#### 饼图：四个关键词所占的比例
- 可以看到，被应用得最多的是“八戒”，其次是“悟空”，应用得最少的是“沙僧”
- 可知，用高德地图api搜索，四个西游记关键词一共有数据2811个
#### 条形统计图：地区分布数量及类型
- 显然，涉及西游记关键词数量最多的省份是江苏省，而在其中餐饮服务又占大多数。说明在全国范围内，西游记对江苏省的影响较大，而江苏人民又把这些关键词多数应用于餐饮服务和生活服务。
- 大多数省份关键词类型都是餐饮服务占的比例最多，但在上海市则是生活服务的比重最大。
- 在青海省，有唯一一个有关于关键词的产业，其类型是生活服务。
#### 条形统计图：类型及关键词
- 八戒确实涉及餐饮服务最多，但餐饮服务业也是四个关键词应用得最多的

- 悟空在生活服务中应用得最多 









<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>
