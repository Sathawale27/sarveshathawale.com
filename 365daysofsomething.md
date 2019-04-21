---
title: Sarvesh Athawale | Android Developer
layout: 365daysofsomething
---
{% for blog in site.365daysofsomething reversed %}
<div>
	<a target="_blank" href="{{ blog.medium_url }}" style="text-decoration: none; display: block;"><p class="text-center project-title">{{ blog.title }}</p></a>
	<p class="text-center project-date">{{ blog.date | date: "%d %B %Y"}}</p>
</div>   
{% endfor %}
