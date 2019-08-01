---
layout: default
tags: coding processing
---

# Presentation list

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url | relative_url }}) ({{ post.date | date_to_string: "ordinal", "GB" }})
{% endfor %}
