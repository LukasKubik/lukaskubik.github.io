---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
공사중 

{% if lukaskubik.googlescholar %}
  You can also find my articles on <u><a href="{{lukaskubik.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
