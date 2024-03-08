---
permalink: /
author_profile: true
redirect_from: 
  - /about/
---

<div class="about-me">
  <h1>About Me</h1>
  <p>Hi!</p>
  <p>I’m Mark, a Master’s student in Language Science and Technology at Saarland University.</p>
  <p>I work as a research assistant at <a href="https://lacoco-lab.github.io/home/">Language, Computation and Cognition Lab</a>. Earlier, I served as a Natural Language Processing engineer at Yandex, developing state-of-the-art LLMs for the Russian language. I also interned at Tinkoff AI and Computational Pragmatics Lab at HSE University.</p>
  <p>Given the early stage of my career, my research interests are broad. They are centered around understanding the internal mechanics of State-of-the-Art neural networks, both artificial and biological. Is there a theoretical model of Transformer-learnable functions? How can we use Deep Learning to draw inferences about the human brain? What interpretable processes happen in LLMs when they answer a query? Those are some of the topics that I am curious about.</p>
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