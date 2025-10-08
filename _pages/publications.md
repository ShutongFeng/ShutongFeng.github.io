---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can find my full list of publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>. Here is a selection of papers and preprints.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
