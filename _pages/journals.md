---
layout: archive
title: "Journals"
permalink: /journals/
author_profile: true
---

<!-- {% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% assign yearArray = "2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009, 2008" | split: ", " %}

{% for i in yearArray %}
### {{i}}
<table>
{% for post in site.journals reversed %}
  {% if post.year == i %}
  <tr>{% include publication.html %}</tr>
  {% endif %}
{% endfor %}
</table>
{% endfor %}
