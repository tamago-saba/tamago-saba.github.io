---
layout: default
title: 記事一覧
permalink: /posts/
---

# 記事一覧

サーバー管理人が気まぐれで投稿する記事の一覧です。

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y/%m/%d" }}
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
