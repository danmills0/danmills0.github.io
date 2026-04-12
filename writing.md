---
layout: default
title: Writing
---

One of my wishes for 2026 is to improve my writing. 
As such you will find below the beginigs of a collection of writings.
I will include book reviews, in part as a way to help me to remember the books I have read.
I will also include writings on govenment science policy, my chosen subject for 2026.
Views outlined here are my own and not those of my employer.

{% for category in site.categories %}
  <h1>{{ category[0] }}</h1>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}