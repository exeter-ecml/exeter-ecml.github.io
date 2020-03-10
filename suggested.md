---
layout: page
title: Suggested Papers
sidebar_link: true
---

{% for paper in site.suggested %}
  [{{ paper.citation}}]({{paper.url}}){:target="_blank"}
{% endfor %}

