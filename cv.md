---
title: Curriculum Vitae
layout: main
nav: 5
---
## Research Interests

Computer, software, and network security, particularly in wireless sensor networks.  Machine learning and artificial intelligence.

## Education

{% include education.html degree=site.data.education.phd %}
{% include education.html degree=site.data.education.ms %}
{% include education.html degree=site.data.education.mba %}
{% include education.html degree=site.data.education.bs %}

## Professional Overview

{% for job in site.data.work %}
{% include work.html job=job %}
{% endfor %}

## Research Summary

<ul class="flat">
{% for area in site.data.research %}
  <li>{{ area.description }} &mdash; <a href="{{site.baseurl}}{{ area.link }}">details</a></li>
{% endfor %}
</ul>

## Publications

### Journal
<ul class="flat citations">
{% include references_by_type.html type="journal" %}
</ul>

### Conference
<ul class="flat citations">
{% include references_by_type.html type="conference" %}
</ul>

## Service

<ul class="flat">
{% for job in site.data.service %}
  <li>{{ job.job }}, {{ job.organization }}, {{ job.date }}</li>
{% endfor %}
</ul>

## Professional Associations

<ul class="flat">
{% for assoc in site.data.associations %}
  <li>Member, {{ assoc }}</li>
{% endfor %}
</ul>
