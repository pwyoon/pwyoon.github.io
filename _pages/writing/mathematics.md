---
layout: archive
title: "Mathematics"
permalink: /writing/mathematics/
author_profile: true
---

[Writing](/writing/) / Mathematics

Expository mathematics, research-related notes, examples, and explanations.

{% assign mathematics_posts = site.categories.mathematics %}

{% if mathematics_posts.size > 0 %}
  {% for post in mathematics_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
No mathematics posts have been published yet.
{% endif %}
