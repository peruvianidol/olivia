---
layout: base
---

{%- for post in collections.posts %}
  * {{ post.data.date | postDate }} &ndash; [{{ post.data.title }}]({{ post.url }})
{%- endfor %}
