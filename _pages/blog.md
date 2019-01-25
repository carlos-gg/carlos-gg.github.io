---
title:  "Blog"
layout: archive
permalink: /blog/
author_profile: true
comments: true
---

Random ideas about open science, AI, Python, scientific computing, machine learning and life in general.

{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}