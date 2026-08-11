---
layout: page
title: 文章
permalink: /articles/
---

## 刑事辩护

{% for post in site.posts %}
{% if post.categories contains "刑事辩护" %}
- [{{ post.title }}]({{ post.url }})（{{ post.date | date: "%Y-%m-%d" }}）
{% endif %}
{% endfor %}

## 时事法律评论

{% for post in site.posts %}
{% if post.categories contains "法律评论" %}
- [{{ post.title }}]({{ post.url }})（{{ post.date | date: "%Y-%m-%d" }}）
{% endif %}
{% endfor %}

## 办案手记

{% for post in site.posts %}
{% if post.categories contains "办案手记" %}
- [{{ post.title }}]({{ post.url }})（{{ post.date | date: "%Y-%m-%d" }}）
{% endif %}
{% endfor %}
