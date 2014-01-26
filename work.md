---
title: Work Experience
layout: main
nav: 2
label: Work
---
{% for entry in site.data.work %}
<a id="{{ entry.id }}"></a>
<h2>{{ entry.employer }}</h2>

<p>{{ entry.start-date }}&mdash;{{ entry.end-date }},&nbsp;&nbsp;<em>{{ entry.title }}</em><p>

<ul>
{% for detail in entry.details %}
<li>{{ detail }}</li>
{% endfor %}
</ul>
{% endfor %}
