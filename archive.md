---
layout: page
title: آرشیو پادکست
---

{% for post in site.categories.podcast %}
  <div>
    <span class="post-date">{{ post.date | jdate: "%b %Y" }}
    <a href="{{ site.baseurl }}{{ post.url }}">
      {{ post.title }}
    </a>
    </span>
  </div>
{% endfor %}

<hr>

<iframe src="https://castbox.fm/app/castbox/player/id1210932?v=8.13.5&autoplay=0" frameborder="0" width="100%" height="500"></iframe>
