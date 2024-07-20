---
layout: page
title: Blog Archivo
---

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li>
        <a href="{{ post.url }}" style="color: #ff4d00;">
          {{ post.date | date: "%B %Y" }} - {{ post.title }}
        </a>
      </li>
    {% endfor %}
  </ul>
{% endfor %}