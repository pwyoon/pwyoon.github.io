---
layout: archive
title: "Reflections & Essays"
permalink: /writing/reflections/
author_profile: true
---

[Writing](/writing/) / Reflections & Essays

Writing about mathematics, education, and just personal experience in general.

{% assign reflection_posts = site.categories.reflections %}

{% if reflection_posts.size > 0 %}
  {% for post in reflection_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
No reflections or essays have been published yet.
{% endif %}
