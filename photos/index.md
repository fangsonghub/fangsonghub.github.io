---
layout: page
title: Photos
permalink: /photos/
---

{% assign photo_pages = site.pages | where: "layout", "photo" | sort: 'date' | reverse %}
{% for photo_page in photo_pages %}
<div class="photo-index-item">
  <a href="{{ photo_page.url }}">{{ photo_page.title }}</a>
</div>
{% endfor %}
