---
layout: page
title: "关于"
permalink: about.html
image: /public/images/lym3.png
color: '#f44336'
index: 5
---


{% comment %}
  This inserts the "about" photo and text from `_config.yml`.
  You can edit it there (jekyll needs restart!) or remove it and provide your own photo/text.
  Don't forget to add the `me` class to the photo, like this: `![alt](src){:.me}`.
{% endcomment %}

{% if site.author.avatar %}
  ![{{site.author.name}}]({{site.author.avatar}}){:.me}
{% endif %}


我是一位不愿透露花色的奶牛猫（如右图示）
