---
layout: default-slate
---

# Publicaciones

***

<ol>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: '%d/%m/%Y' }}
      <a href="/blog/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ol>



