---
permalink: /
author_profile: true
redirect_from: 
  - /about/
---

<div class="about-me">
  <h1>About Me</h1>
  <p>Hi!</p>
  <p>My name is Mark. I am a Natural Language Processing Engineer interested in Language Models and other sci-fi Deep Learning inventions.</p>
  <p>At the moment I am between my Bachelor degree from Higher School of Economics and Masters on Computational Linguistics in Saarland University. I also work at the LLM team at Yandex, where we build giant models used in products of Yandex.</p>
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