---
layout: default
title: Archive
permalink: /archive/
---

<h2 class="section-title">Archive</h2>

<div class="archive-list">
{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'"  %}
{% for curYear in postsByYear %}
  <h2 class="archive-year" id="{{ curYear.name }}-ref">{{ curYear.name }}</h2>
  {% assign postsByYearMonth = curYear.items | group_by_exp:"post", "post.date | date: '%B'"  %}
  {% for curMonth in postsByYearMonth %}
    <h3 class="archive-month">{{ curMonth.name }}</h3>
    {% for post in curMonth.items %}
      <div class="archive-item">
        <a href="{{ post.url }}">
          <span>{{ post.title }}</span>
          <span class="archive-date">{{ post.date | date: "%B %d, %Y" }}</span>
        </a>
      </div>
    {% endfor %}
  {% endfor %}
{% endfor %}
</div>