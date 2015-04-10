---
layout: page
title: Filosofía
---

#Apuntes de Filosofía

<ul>
	{% for post in site.categories.filosofia %}
		<li> <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a> </li>
	{% endfor %}
</ul>