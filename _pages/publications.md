---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my papers on [my Semantic Scholar profile](https://www.semanticscholar.org/author/Mark-Rofin/2187576116).

{% include base_path %}

{% for post in site.publications reversed %}
  <h2>{{ post.title }}</h2>
  <p><em>{{ post.authors }}</em></p>
  <p>{{ post.excerpt }}</p>
  <a href="{{ post.paperurl }}">Download paper here</a>
  <hr>
{% endfor %}
