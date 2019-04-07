---
title: Sarvesh Athwale | Android Developer
layout: default
---
{% for blog in site.blogs reversed %}
<div>
	<a target="_blank" href="{{ blog.medium_url }}" style="text-decoration: none; display: block;"><p class="text-center project-title">{{ blog.title }}</p></a>
	<p class="text-center project-date">{{ blog.date | date: "%d %B %Y"}}</p>
	<div class="wrap">
		<a target="_blank" href="{{ blog.medium_url }}" class="project-image" style="background-image: url({{ blog.img_url }});"></a>
		<p class="project-content">{{ blog.description }}</p>
	</div>
</div>   
{% endfor %}
