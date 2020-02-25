# Welcome

In this blog, I write about my experiences with my professional career in the software development industry of Africa.

<p>
	<a href="https://dev.to/fordarnold">
		<img src="https://d2fltix0v2e0sb.cloudfront.net/dev-badge.svg" alt="Robin Hood's DEV Profile" height="30" width="30">
	</a>
	<br/>
	<a href="https://dev.to/fordarnold">
		<img src="https://www.codewars.com/users/fordarnold/badges/small" alt="Robin Hood on Codewars">
	</a>
</p>

## Blog Posts

<ul>
	{% for post in site.posts %}
	<li>
		<a href="{{ post.url }}">{{ post.title }}</a>
		<p>{{ post.excerpt }}</p>
	</li>
	{% endfor %}
</ul>
