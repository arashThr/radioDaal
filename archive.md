---
layout: page
title: آرشیو پادکست
---

<iframe src="https://castbox.fm/app/castbox/player/id1001363?v=4.0.11" frameborder="0" width="100%" height="400"></iframe>

<hr>

{% for post in site.categories.podcast %}
  <div>
    <span class="post-date">{{ post.date | jdate: "%b %Y" }}
    <a href="{{ site.baseurl }}{{ post.url }}">
      {{ post.title }}
    </a>
    </span>
  </div>
{% endfor %}
