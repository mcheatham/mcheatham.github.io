---
title: Resume
layout: main
nav: 6
---
## Education

{% include education.html degree=site.data.education.phd %}
{% include education.html degree=site.data.education.ms %}
{% include education.html degree=site.data.education.mba %}
{% include education.html degree=site.data.education.bs %}

## Professional Experience

{% for job in site.data.work %}
{% include work.html job=job %}
{% endfor %}

## Certifications

<ul class="flat">
{% for cert in site.data.certifications %}
  <li>{{ cert }}</li>
{% endfor %}
</ul>

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

