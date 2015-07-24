---
layout: page
title: Logos
permalink: /logos/
---

I've made a few pages demonstrating some techniques for using <a href="http://www.logos.com/">Logos Bible Software</a>. You can view them using the list below.

## Installation and Usage Guides

See the pages listed below for further documentation.

<ul>
	{% for post in site.categories.logos %}
		<li><a href="{{site.baseurl}}{{post.url}}">{{ post.title }}</a></li>
	{% endfor %}
</ul>
