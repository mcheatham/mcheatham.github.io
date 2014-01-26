---
title: Curriculum Vitae (abbreviated)
layout: main
nav: 8
label: CV
---
## Research Interests

Applying machine learning, artificial intelligence, and semantic technologies 
to real-world problems, with a current focus on software reverse engineering 
and privacy protection in Big Data.

## Education

<table id="education" style="width:100%">
<tbody>
{% include education.html degree=site.data.education.phd %}
{% include education.html degree=site.data.education.ms %}
{% include education.html degree=site.data.education.mba %}
{% include education.html degree=site.data.education.bs %}
</tbody>
</table>

## Professional Overview

<table id="work" style="width:100%">
<tbody>
{% for job in site.data.work %}
{% include work.html job=job %}
{% endfor %}
</tbody>
</table>

## Professional Associations

<ul class="flat">
{% for assoc in site.data.associations %}
  <li>Member, {{ assoc }}</li>
{% endfor %}
</ul>
