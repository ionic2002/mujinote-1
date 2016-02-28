---
layout: index
title: donghyuc-kim 무지노트
---

<ul class="posts">
	{% for post in site.posts %}
		<li>
			<a href=".{{ post.url }}">{{ post.title }}</a>
		</li>
	{% endfor %}
</ul> 
