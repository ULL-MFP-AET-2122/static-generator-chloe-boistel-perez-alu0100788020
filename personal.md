---
title: Mis publicaciones personales
permalink: /personal
toc: true
layout: single
---

 {%- for post in site.categories["personal"]  %}
* [{{post.title}}]({{post.url}})
 {% endfor %}