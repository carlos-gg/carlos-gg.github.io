---
title:  "Blog"
layout: archive
permalink: /blog/
author_profile: true
comments: true
---

Random ideas on open science, exoplanets, scientific computing and machine learning.

{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}