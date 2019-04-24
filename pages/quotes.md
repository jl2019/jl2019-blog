---
layout: page
title: Quotes
permalink: /quotes/
---
{% for quote in site.quotes %}
1. [{{ quote.author }}]({{ quote.url }})
{% endfor %}
