---
layout: page
title: Blog Archivo
---

<div style="text-align: center;">
  <a href="https://community.rabbit.tech/t/r1-en-espana">
    <img src="/assets/images/rabbit_smart.svg" alt="Archivo" width="128" height="128">
  </a>
</div>

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
