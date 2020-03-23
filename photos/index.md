---
layout: page
title: Photos
desc: Activities
permalink: /photos/
description: ""
---

## Photo Sets 
<ul>
  {% comment %}
    Get all "photo" pages and display a list with links to them.
  {% endcomment %}
  {% assign photo_pages = site.pages | where: "layout", "photo" | sort: 'date' | reverse %}
  {% for photo_page in photo_pages %}
    <li>
      <a href="{{ photo_page.url | prepend: site.baseurl }}">{{ photo_page.title }}</a>
    </li>
  {% endfor %}
</ul>
