---
layout: splash
permalink: /blog/
title: "Blog"
linktext: "Blog"
lang: de
ref: blog
header:
  overlay_color: "#808080"
  overlay_filter: 0.5
  overlay_image: assets/images/archive.jpg
  cta_label: 
  cta_url: 
  caption: 
excerpt: 
---

{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  <p>{{ post.date | date_to_string }}</p>
  <p>{{ post.content }}</p>
{% endfor %}




