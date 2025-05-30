---
layout: home
---

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
      <p>{{ post.description }}</p>
    </li>
  {% endfor %}
</ul>
