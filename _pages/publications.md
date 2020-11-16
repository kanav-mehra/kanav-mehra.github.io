---
layout: archive
permalink: /publications/
title: "Publications"
author_profile: true
---

{% if author.uri %}
  You can also find my articles on <u><a href="https://scholar.google.com/citations?user=FKLCfnYAAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
