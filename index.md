---
layout: page
title: Home
nav: true
nav_order: 1
---


# yokoso

bla bla bla

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <p>{{ post.content | truncate : 200 }}</p>
  </li>
{% endfor %}
</ul>
