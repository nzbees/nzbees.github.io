---
layout: page
title: Software
image:
  feature: image_05.jpg
  credit: Kaitiaki Creations
---


<ul class="post-list">
{% for post in site.categories.software %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></background></li>
{% endfor %}
