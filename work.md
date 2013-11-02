---
title: Work Experience
layout: main
nav: 4
---
{% for entry in site.data.work %}
<a id="{{ entry.id }}"></a>
<h2>{{ entry.employer }}</h2>

<p>{{ entry.start-date }}&mdash;{{ entry.end-date }},&nbsp;&nbsp;<em>{{ entry.title }}</em><p>

<p>{{ entry.details }}</p>
{% endfor %}
