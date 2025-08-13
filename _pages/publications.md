---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Working Papers

{% for post in site.publications reversed %}
  {% if post.path contains 'wp' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}