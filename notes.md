---
layout: default
title: Notes
permalink: /notes/
---

# Notes

{% assign upnote_posts = site.posts | where_exp: "post", "post.upnote_source" %}
{% if upnote_posts.size > 0 %}
  {% for post in upnote_posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%d %B %Y" }}
  {% endfor %}
{% else %}
Notes from UpNote will appear here after they are published.
{% endif %}
