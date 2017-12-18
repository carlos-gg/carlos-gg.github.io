---
title:  "Blog"
layout: archive
permalink: /blog/
author_profile: true
comments: true
---

Test blog page.

{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}