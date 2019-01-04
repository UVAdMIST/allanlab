---
title: "Home"
layout: textlay
excerpt: "dMIST Research Group Website"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p style="margin-bottom:30px"><b>{{ article.date }}</b> <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
