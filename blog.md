---
title: Mis publicaciones sobre el Blog
permalink: /blog
toc: true
layout: single
---

 {%- for post in site.categories["blog"]  %}
* [{{post.title}}]({{post.url}})
 {% endfor %}