---
layout: page
title: Speaking Events
permalink: /speaking/
---
***
{% for item in site.data.phd_speaking %}
  * <b> {{ item.Date }}: </b>
  {{ item.Role }} ({{ item.Location }}) <br>
  {{ item.Title }},
  <i> {{ item.Host }} </i>
{% endfor %}
