---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my papers on [my Google Scholar profile](https://scholar.google.com/citations?user=5Bk9qNYAAAAJ&hl=en)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
