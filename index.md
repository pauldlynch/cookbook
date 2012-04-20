---
layout: page
title: Student Cookbook
tagline: Easy recipes for everyday living
---
{% include JB/setup %}

<h2>All Recipes</h2>
<ul>
	{% assign pages_list = site.pages %}
	{% assign group = 'recipe' %}
{% include JB/pages_list %}
</ul>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
