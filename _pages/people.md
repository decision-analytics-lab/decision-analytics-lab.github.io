---
title: "People"
layout: splash
header:
  overlay_image: /assets/images/home.jpg
permalink: /people/index.html
date: 2018-01-07

gallery:
  - url: /assets/images/students/Dong Junyi.jpg
    title: "Dong Junyi"
  - url: /assets/images/students/Fu Qiaochu.jpg
    title: "Fu Qiaochu"
  - url: /assets/images/students/He Xing.jpg
    title: "He Xing"
  - url: /assets/images/students/Lu Jialiang.jpg
    title: "Lu Jialiang"
  - url: /assets/images/students/Wu Tongwen.jpg
    title: "Wu Tongwen"
  - url: /assets/images/students/Zheng Zhenhan.jpg
    title: "Zheng Zhenhan"
---

{% for g in page.gallery %}
<div class="member"><img src="{{g.url}}"><h3> {{g.title}}</h3></div>
{% endfor %}
