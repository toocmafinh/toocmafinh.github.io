---
layout: default
---

## About

Hey!

I'm Phuong :D

I write because I'm afraid someday I might forget everything or I might be forgotten.


## Latest Posts

<ul>
{% assign excerpt_length = site.excerpt_length | default: 50 %}
{% for post in site.posts limit: 20 %}
  <li>
    <h3>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h3>
    <p>
      {% if post.subtitle %}
        <strong>{{ post.subtitle }}</strong> - 
      {% endif %}
      {{ post.content | strip_html | truncatewords: excerpt_length }}
    </p>
    <p>
      <small>
        Published on {{ post.date | date: "%A, %d %B %Y" }}
      </small>
    </p>
  </li>
{% endfor %}
</ul>

