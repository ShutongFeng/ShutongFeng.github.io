---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can find my full list of publications on my [Google Scholar profile](https://scholar.google.com/citations?user=fpeCQYIAAAAJ&hl=en). Here is a selection of papers and preprints.
{% endif %}

{% include base_path %}

You can find my full list of publications on my [Google Scholar profile](https://scholar.google.com/citations?user=fpeCQYIAAAAJ&hl=en). Here is a selection of papers and preprints.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
