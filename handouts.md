---
layout: page
title: Handouts
permalink: /handouts/
include: true
order: 4
---

# Handouts

*Please do not cite or circulate without my permission. Thank you.*

<h2>{{ site.data.undergraduate-handouts.docs_list_title }}</h2>
<ul>
   {% for item in site.data.undergraduate-handouts.docs %}
      <li><a href="{{ item.url }}" alt="{{ item.title }}">{{ item.title }}</a> ({{ item.place }}; {{ item.date }})</li>
   {% endfor %}
</ul>
