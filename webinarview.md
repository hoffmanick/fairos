{% assign posts = site.posts | where_exp: "item", "item.tags contains 'webinar'" %}
{% for post in posts limit:5 %}
  {{ post.title }}
{% endfor %}
