---
title: "Welcome to my blog"
date: 2024-07-06
---

## Mere Blog Theme

Mere is a minimal and simple blog theme, and nothing more, for use with Jekyll and GitHub Pages.

This is the homepage, it has some space at the top to display your introduction text and then it displays the latest 6 posts below.
john
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
