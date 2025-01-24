---
layout: default
---

<ul class="post-feed">
{% assign excerpt_length = site.excerpt_length | default: 50 %}
{% for post in site.posts limit: 20 %}
  <li>
    <h2>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h2>
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

