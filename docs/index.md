---
layout: default
---

Here are my posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%F" }} {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
