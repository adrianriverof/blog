---
layout: default-slate
---

# Publicaciones

***

<ol>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: '%d/%m/%Y' }}
      <a href="{{ post.permalink }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ol>



