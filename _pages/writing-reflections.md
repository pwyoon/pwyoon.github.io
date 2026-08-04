---
layout: archive
title: "Reflections & Essays"
permalink: /writing/reflections/
author_profile: true
---

Reflections on mathematics, education, research, and personal experience.

{% assign reflection_posts = site.categories.reflections %}

{% if reflection_posts.size > 0 %}
  {% for post in reflection_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
No reflections or essays have been published yet.
{% endif %}
