---
title: "People"
layout: splash
header:
  overlay_image: /assets/images/home.jpg
permalink: /people/index.html
date: 2018-01-07

gallery:
  - url: /assets/images/students/Dong Junyi.jpg
    image_path: /assets/images/students/Dong Junyi.jpg
    alt: "Dong Junyi"
    title: "Dong Junyi"
  - url: /assets/images/students/Fu Qiaochu.jpg
    image_path: /assets/images/students/Fu Qiaochu.jpg
    alt: "Fu Qiaochu"
    title: "Fu Qiaochu"
  - url: /assets/images/students/He Xing.jpg
    image_path: /assets/images/students/He Xing.jpg
    alt: "He Xing"
    title: "He Xing"
  - url: /assets/images/students/Lu Jialiang.jpg
    image_path: /assets/images/students/Lu Jialiang.jpg
    alt: "Lu Jialiang"
    title: "Lu Jialiang"
  - url: /assets/images/students/Wu Tongwen.jpg
    image_path: /assets/images/students/Wu Tongwen.jpg
    alt: "Wu Tongwen"
    title: "Wu Tongwen"
  - url: /assets/images/students/Zheng zhenhan.jpg
    image_path: /assets/images/students/Zheng Zhenhan.jpg
    alt: "Zheng zhenhan"
    title: "Zheng zhenhan"
---

{% for g in page.gallery %}
<div class="member"><img src="{{g.url}}"><h3> {{g.title}}</h3></div>
{% endfor %}
