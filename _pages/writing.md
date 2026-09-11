---
layout: archive
title: "Writing"
permalink: /writing/
author_profile: true
---

---
layout: archive
title: "Writing"
permalink: /writing/
author_profile: true
---

I write about mathematics, research, education, and other topics that interest me.

## Recent Posts

{% for post in site.posts limit:6 %}

**[{{ post.title }}]({{ post.url | relative_url }})**  
*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt | strip_html | truncate: 220 }}

{% endfor %}

## Browse by Topic

**[Mathematics](/writing/mathematics/)**  
Expository mathematics, research-related notes, examples, and explanations.

**[Reflections & Essays](/writing/reflections/)**  
Writing about education, research, my life path, travel, and other experiences.

## Earlier Writing

Before starting this site, I wrote regularly on
[Quora](https://www.quora.com/), where I was named a Quora Top Writer in 2018.

I also wrote a few pieces for the
[Johns Hopkins News-Letter](https://www.jhunewsletter.com/).
