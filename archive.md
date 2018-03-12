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
