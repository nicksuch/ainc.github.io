---
layout: page
title: 
tagline: Learn to code with Awesome Inc
---
{% include JB/setup %}

{% for post in site.posts %}
<h1><a href='{{post.url}}'>{{post.title}}</a></h1>
<em>{{ post.date | date: "%b %d, %Y" }}</em>
<div>{{ post.content }}</div>
{% endfor %}



