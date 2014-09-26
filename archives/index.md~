---
layout: page
title: Image Archives
image:
  feature: image_06.jpg
  credit: Kaitiaki Creations
---

<ul class="post-list">
{% for post in site.categories.archives %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>