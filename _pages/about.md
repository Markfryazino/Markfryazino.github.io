---
permalink: /
author_profile: true
title: "Home"
redirect_from: 
  - /about/
layout: default
---

<div class="about-me">
  <h1>About Me</h1>
  <p>Welcome to my personal website! I'm a researcher in the field of machine learning and natural language processing. My work involves exploring and developing new techniques for understanding and generating human language.</p>
</div>

<div class="news-section">
  <h1>News</h1>
  {% for post in site.news reversed %}
    <div class="news-item">
      <h2>{{ post.date | date: "%B %Y" }}</h2>
      <p>{{ post.content }}</p>
    </div>
    <hr>
  {% endfor %}
</div>