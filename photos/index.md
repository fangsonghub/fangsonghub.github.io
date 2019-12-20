---
layout: page
title: Photos
permalink: /photos/
description: "ENTER HERE"
---

<h1>Photo Sets</h1>
<ul>
  {% comment %}
    Get all "photo" pages and display a list with links to them.
  {% endcomment %}
  {% assign photo_pages = site.pages | where: "layout", "photo" %}
  {% for photo_page in photo_pages %}
    <li>
      <a href="{{ photo_page.url | prepend: site.baseurl }}">{{ photo_page.title }}</a>
    </li>
  {% endfor %}
</ul>
