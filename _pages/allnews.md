---
title: "News"
layout: textlay
excerpt: "IMICS Lab at Texas State University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<b>{{ article.date }}</b> <br/>
{{ article.headline | markdownify}}<br/>
{% endfor %}
