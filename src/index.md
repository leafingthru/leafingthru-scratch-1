---
title: Building an 11ty site from scratch
layout: base.njk
---

## Learning new things

I sometimes think I'm too old for this. But I feel good after figuring things out.

{% for page in collections.pages %}

- [{{ page.data.title }}]({{ page.url }})

{%- endfor %}
