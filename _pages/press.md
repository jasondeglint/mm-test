---
layout: page
title: Press
permalink: /press/
---
***
{% for item in site.data.news_items %}
  <b> {{ item.Date }}: </b>
  <a href="{{ item.URL }}"> {{ item.Title }} </a>
  by <i> {{ item.Outlet }} </i>

{% endfor %}
