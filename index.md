---
layout: page
---
{% include JB/setup %}

{% for post in site.posts limit:3 %}
  <ul class="post">
    »{{ post.date | date_to_string }}
    <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
    {{post.content}}
  </ul>
{% endfor %}
