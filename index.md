---
layout: default
---

Burada aklıma gelenleri paylaşıyorum.

### Son Yazılar

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%d.%m.%Y" }})</small>
    </li>
  {% endfor %}
</ul>
