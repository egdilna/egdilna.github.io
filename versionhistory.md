---
layout: page
title: Protokol verzí portálového engine
---

{% for revize in site.data.versionlist %}
<p>{{ revize.datum }} (verze {{ revize.verze }}): {{ revize.popis }}</p>
{% endfor %}