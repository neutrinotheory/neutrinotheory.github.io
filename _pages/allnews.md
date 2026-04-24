---
title: "N E W S"
layout: textlay
excerpt: "Neutrino Theory at Leiden University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p><strong>{{ article.date }}</strong><br>{{ article.headline | markdownify | remove: '<p>' | remove: '</p>' }}</p>
{% endfor %}
