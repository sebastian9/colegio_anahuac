---
layout: page
title: Producción y Animación  con Elementos Multimedia
---

#Apuntes de Producción y Animación  con Elementos Multimedia

<ul>
	{% for post in site.categories.animacion %}
		<li> <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a> </li>
	{% endfor %}
</ul>