---
layout: default
title: Blog
permalink: /blog/
---

# Blog

<table class="postlist">
  <tr><th>Date</th><th>Title</th></tr>
{%- for post in site.posts %}
  <tr>
    <td class="date">{{ post.date | date: "%b %-d, %Y" }}</td>
    <td><a href="{{ post.url }}">{{ post.title }}</a></td>
  </tr>
{%- endfor %}
</table>
