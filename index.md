--- 
layout: default 
title: Home 
---
{% for post in paginator.posts %}
{{ post.title }}
{{ post.date | date_to_string }} {{ post.content }}
{% endfor %}
{% if paginator.next_page %} Older {% else %} Older {% endif %} {% if paginator.previous_page %} {% if paginator.page == 2 %} Newer {% else %} Newer {% endif %} {% else %} Newer {% endif %}