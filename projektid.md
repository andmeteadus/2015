---
layout: page
title: Projektid
---

Tudengite poolt tehtud projektid. Projekti juhendi leiad [siit](http://andmeteadus.github.io/2015/projekt_juhend/).
<br><br>

{% for post in site.posts %}
## [ {{ post.title }} ](..{{ post.url }})
  {{ post.content | strip_html | truncatewords:30}}
  [ (loe edasi) ](..{{ post.url }})
  <br><br>
  
{% endfor %}