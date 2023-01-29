---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=DzAh3ykAAAAJ&hl=en&oi=ao).

# Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Presentations

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
