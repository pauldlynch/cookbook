---
layout: page
title: Student Cookbook
tagline: Easy recipes for everyday living
---
{% include JB/setup %}

##Featured Recipes

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

<!-- ><ul>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=101KitchenGear.pages">101 &#8211; Kitchen Gear</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=Macaroni_Cheese.pages">Macaroni Cheese</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=ChickenHamPie.pages">Chicken &amp; Ham Pie</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=Chili.pages">Chili</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=BeefStew.pages">Beef Stew (and Pie)</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=Dhal.pages">Tarka Dhal</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=VegetableCurry.pages">Vegetable Curry</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=TomatoSauce.pages">Tomato Sauce</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=SausageSauce.pages">Sausage Sauce for Pasta</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=SalmonPasta.pages">Pasta with Smoked Salmon</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=Meatballs.pages">Meatballs</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=BlackBeanSoup.pages">Black Bean Soup</a></li>
<li><a href="http://public.iwork.com/document/?a=p38454520&amp;d=SemiFreddo.pages">Semi Freddo</a></li>
</ul> -->


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
