---
layout: home
title: "Welcome to My Blog"
---
## Latest Posts
{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}