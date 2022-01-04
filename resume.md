---
title: Resume
layout: main
nav: 9
---

## Education

<table id="education" style="width:100%">
<tbody>
{% include education.html degree=site.data.education.phd %}
{% include education.html degree=site.data.education.ms %}
{% include education.html degree=site.data.education.mba %}
{% include education.html degree=site.data.education.bs %}
</tbody>
</table>

## Professional Experience

<table id="work" style="width:100%">
<tbody>
{% for job in site.data.work %}
{% include work.html job=job %}
{% endfor %}
</tbody>
</table>

<!--
## Certifications

<ul class="flat">
{% for cert in site.data.certifications %}
  <li>{{ cert }}</li>
{% endfor %}
</ul>
-->

## Computer Experience

<table id="skills">
  <thead>
    <th></th>
    <th>Proficient</th>
    <th>Working knowledge</th>
  </thead>
  {% for skill in site.data.skills %}
  <tbody>
    <th>{{ skill.group }}</th>
    <td>
      <ul class="flat">
        {% for p in skill.proficient %}
        <li>{{ p }}</li>
        {% endfor %}
      </ul>
    </td>
    <td>
      <ul class="flat">
        {% for f in skill.familiar %}
        <li>{{ f }}</li>
        {% endfor %}
      </ul>
    </td>
  </tbody>
  {% endfor %}
</table>
