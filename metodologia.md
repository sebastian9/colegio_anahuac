---
layout: page
title: Metodología de la Investigación
---

#Apuntes de Metodología de la Investigación

<ul>
	{% for post in site.categories.metodologia %}
		<li> <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a> </li>
	{% endfor %}
</ul>