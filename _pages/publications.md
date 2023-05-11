---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my papers on [my Google Scholar profile](https://scholar.google.com/citations?user=AX0GLYIAAAAJ&hl=en).

{% include base_path %}

{% for post in site.publications reversed %}
  <h2>{{ post.title }}</h2>
  <p>{{ post.excerpt }}</p>
  <a href="{{ post.paperurl }}">Download paper here</a>
  <hr>
{% endfor %}
