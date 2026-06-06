---
layout: page
title: Home
---


# Yōkoso

Here's my website, called web-sight, lol.
I don't know how *alive* this website will be but eh.. 

If you enjoy **Modules** feel free to take a look around !

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <p>{{ post.content | truncate : 200 }}</p>
  </li>
{% endfor %}
</ul>
