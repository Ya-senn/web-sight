---
layout: page
title: Home
nav: true
---


# yokoso

bla bla bla

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <p>{{ post.excerpt }}</p>
  </li>
{% endfor %}
</ul>
