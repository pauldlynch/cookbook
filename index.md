---
layout: page
title: Student Cookbook
tagline: Easy recipes for everyday living
---
{% include JB/setup %}

## Featured Recipes

- [101–Kitchen Gear](assets/101KitchenGear.pdf)
- [Macaroni Cheese](assets/Macaroni_Cheese.pdf)
- [Chicken & Ham Pie](assets/ChickenHamPie.pdf)
- [Chili](assets/Chili.pdf)
- [Beef Stew (and Pie)](assets/BeefStew.pdf)
- [Tarka Dhal](assets/Dhal.pdf)
- [Vegetable Curry](assets/VegetableCurry.pdf)
- [Tomato Sauce](assets/TomatoSauce.pdf)
- [Sausage Sauce for Pasta](assets/SausageSauce.pdf)
- [Pasta with Smoked Salmon](assets/SalmonPasta.pdf)
- [Meatballs](assets/Meatballs.pdf)
- [Black Bean Soup](assets/BlackBeanSoup.pdf)
- [Semi Freddo](assets/SemiFreddo.pdf)


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
