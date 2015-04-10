---
layout: page
title: Psicología
---

#Apuntes de Psicología

<ul>
	{% for post in site.categories.psicologia %}
		<li> <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a> </li>
	{% endfor %}
</ul>