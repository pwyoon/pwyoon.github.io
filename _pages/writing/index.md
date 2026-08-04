
---
layout: archive
title: "Writing"
permalink: /writing/
author_profile: true
---

## Earlier Writing

Before starting this site, I wrote regularly on
[Quora](https://www.quora.com/profile/Phillip-Yoon-2), where I was named a Quora Top Writer in 2018. 

## Mathematics

Expository mathematics, research-related notes, examples, and explanations.

[View mathematics posts](/writing/mathematics/){: .btn .btn--primary}

## Reflections & Essays

Writing about mathematics, education, and just personal experience in general.

[View reflections and essays](/writing/reflections/){: .btn .btn--primary}

## Recent Posts

{% for post in site.posts limit:6 %}
  {% include archive-single.html %}
{% endfor %}
