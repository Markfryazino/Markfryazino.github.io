---
permalink: /
author_profile: true
redirect_from: 
  - /about/
---

<div class="about-me">
  <h1>About Me</h1>
  <p>Hi!</p>
  <p>I'm Mark, a Natural Language Processing Engineer with a keen interest in Language Models and other sci-fi advancements in the realm of Deep Learning.</p>
  <p>Currently, I am transitioning from completing my Bachelor's degree in Computer Science at Higher School of Economics to pursuing a Master's degree in Computational Linguistics at Saarland University. In conjunction with my studies, I am a part of the LLM team at Yandex, contributing to the development and integration of models that fuel an array of the company's products.</p>
</div>

<hr>

<div class="news-section">
  <h1>News</h1>
  {% for post in site.news reversed %}
    <div class="news-item">
      <p><b>{{ post.date | date: "%B %Y" }} &mdash; </b> {{ post.content }}</p>
    </div>
  {% endfor %}
</div>