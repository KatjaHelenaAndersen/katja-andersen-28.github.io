---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Published papers

{% for post in site.publications reversed %}
  {% if post.path contains 'published' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Working papers

{% for post in site.publications reversed %}
  {% if post.path contains 'wp' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Selected work in progress