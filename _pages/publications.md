---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Research papers

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Review papers

{% for post in site.reviewpublications reversed %}
  {% include archive-single-review.html %}
{% endfor %}
