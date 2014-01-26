---
title: Teaching Experience
layout: main
nav: 6
label: Teaching
---
{% for entry in site.data.teaching %}
<a id="{{ entry.id }}"></a>
<h2>{{ entry.employer }}</h2>

<p>{{ entry.start-date }}{% if entry.end-date %}&mdash;{{ entry.end-date }}{% endif %},&nbsp;&nbsp;<em>{{ entry.title }}</em><p>

<ul>
{% for detail in entry.details %}
<li>{{ detail }}</li>
{% endfor %}
</ul>
{% endfor %}
