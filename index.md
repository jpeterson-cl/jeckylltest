---
layout: post
title: Blogging Like a Hacker
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="./jeckylltest{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>