---
layout: default
title: "news"
permalink: /news
---
<h1> Ethical Open Science in the News </h1>

{% for post in site.posts %}
- {{ post.date | date_to_string }}: [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
