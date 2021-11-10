---
layout: page
title: Archive
permalink: /posts/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> (posted {{ post.date | date: "%B %d %Y" }})
    </li>
  {% endfor %}
</ul>