# Welcome

In this blog, I write about my experiences in my professional career in the software development industry of Africa.

### Blog Posts

<ul>
	{% for post in site.posts %}
	<li>
		<a href="{{ post.url }}">{{ post.title }}</a>
		{{ post.excerpt }}
	</li>
	{% endfor %}
</ul>