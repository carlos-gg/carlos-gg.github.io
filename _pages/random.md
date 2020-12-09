---
title:  "Random stuff"
layout: archive
permalink: /random/
author_profile: true
classes: wide
---

Random ideas and failed attempt to create a blog.

---
_"Essentially, all models are wrong, but some are useful."_ - George Box.

_"...if the model is going to be wrong anyway, why not see if you can get the computer to ‘quickly’ learn a model from the data, rather than have a human laboriously derive a model from a lot of thought."_ -Peter Norvig.

---

{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}