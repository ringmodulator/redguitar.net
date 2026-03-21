---
layout: post.njk
title: Upcoming Shows
---

- May 27, 2026: North Adams, MA, Belltower Records, with [The Early](https://theearly.bandcamp.com/album/i-want-to-be-ready) and [Bent Light](https://thefamilystoned.bandcamp.com/album/see-him-clearly)

<ul>
	{% for item in shows.items %}
	<li>
		{item.date}: {item.city}, {item.venue} with {item.acts}
	</li>
	{% endfor %}
</ul>