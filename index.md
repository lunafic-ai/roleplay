---
layout: page
title: AI Roleplay Guides
permalink: /
---

Plain, honest guides to AI roleplay: how memory works in long stories, how to keep a story consistent, playing your own character, scenes with many characters, dialogue in Japanese with a translation, and how today's apps compare.

These guides are written by the team behind [Lunafic](https://lunafic.ai), an AI roleplay app. We say so on every page, we describe other apps fairly, and we list Lunafic's own limits. Each guide shows the date its facts were last checked.

## Guides

{% assign guides = site.guides | where_exp: "g", "g.date <= site.time" | sort: "date" | reverse %}
{% if guides.size > 0 %}
<ul>
{% for g in guides %}
  <li><a href="{{ g.url | relative_url }}">{{ g.title }}</a>{% if g.description %}<br>{{ g.description }}{% endif %}</li>
{% endfor %}
</ul>
{% else %}
The first guides are on their way.
{% endif %}
