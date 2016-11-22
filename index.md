---
layout  : default
title   : "New Media Design & Development"
---

SLA
===

<ul class="posts">
{% for post in site.posts %}
    <li><a href="{{ post.url }}" title="">{{ post.title }}</a> {{ post.excerpt | strip_html | truncatewords:5  }} </li>
{% endfor %}
</ul>