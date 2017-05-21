---
layout: page
title: Home
---

# A city in the desert. A culture of possibility. A network of dreamers and doers.

### Město v poušti. Kultura možností. Síť snílků a mužů činu.



## Posts

See the posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
