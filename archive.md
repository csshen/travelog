---
layout: page
title: archive
---

<div class="post-date" style="border: None">
	{% for post in site.posts %}
		<p><a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a></p>
	{% endfor %}
</div>