---
permalink: "/posts/"
sitemap: true
robots-allow: true
layout: page
title: Posts
heading: Blog
subtitle: Post here
published: true

---
<section>
	<div>
	<ul>
  		{% for post in site.posts %}
    	<li>
      		<h2>{{ post.title }}</h2>
			<div>
				<p>
					{{ post.excerpt }}
				</p>
				<p>
					<a href="{{ post.url }}">Read More &rarr;</a>
				</p>
			</div>
    	</li>
  		{% endfor %}
	</ul>
	</div>
</section>