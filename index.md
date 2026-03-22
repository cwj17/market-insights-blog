---
layout: default
---

# Market Insights: AI & Investing

Welcome to the automated market insights blog. This platform tracks the latest strategies from top investors and extracts actionable insights.

## Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
