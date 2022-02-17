---
layout: page
title: "友链"
permalink: links.html
index: 3
---

友情链接~

## 【美丽模板的作者】

<section class="most-valuable-link">
  {% for link in site.data.links['one'] %}
  <a class="mvl-link" href="{{link.url}}">
    <img src="{{link.avatar}}">
    <h4>{{link.name}}</h4>
    <div>{{link.desc}}</div>
  </a>
  {% endfor %}
</section>

<!-- ## 其他友链，

{% for link in site.data.links['two'] %}
* [{{link.name}}]({{link.url}})
{% endfor %} -->
