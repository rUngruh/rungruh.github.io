---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% for post in site.news reversed %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p><em>{{ post.date | date: "%B %-d, %Y" }}</em></p>
  {{ post.excerpt }}
{% endfor %}