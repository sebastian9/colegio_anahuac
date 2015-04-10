---
layout: page
title: Elaborar Páginas Web
---

#Apuntes de Elaborar Páginas Web

<ul>
	{% for post in site.categories.web %}
		<li> <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a> </li>
	{% endfor %}
</ul>