---
layout: page
title: Papers
---

{% for item in site.data.papers %}
<center><a name="{{ item.year }}">{{ item.year }}</a></center>
{% for paper in item.articles %}
<p>{{ paper }}</p>
{% endfor %}
<br>
{% endfor %}