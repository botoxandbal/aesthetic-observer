---
layout: home
title: The Aesthetic Observer
---

## Latest Articles

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.description }}</p>
    </li>
  {% endfor %}
</ul>
