---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

{% for post in site.research %}
  <h2><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
