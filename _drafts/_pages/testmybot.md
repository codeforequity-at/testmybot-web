---
title: index.md
date: 2018-01-30 12:00:10 +0000
---
<ul>

{% for post in site.posts %}

<li>

<a href="{{ post.url }}">{{ post.title }}</a>

</li>

{% endfor %}

</ul>