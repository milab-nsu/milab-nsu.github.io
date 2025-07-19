---
title: "News"
layout: textlay
excerpt: "MILab"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}

<strong>{{ article.date }}</strong>

{{ article.headline | markdownify}}

{% endfor %}
