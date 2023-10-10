---
permalink: /
author_profile: true
redirect_from: 
  - /about/
---

<div class="about-me">
  <h1>About Me</h1>
  <p>Hi!</p>
  <p>I’m Mark, a Master’s student in Language Science and Technology at Saarland University. In 2023, I received a B.S. in Computer Science from Higher School of Economics in Moscow, majoring in Machine Learning.</p>
  <p>I have a keen interest in Large Language Models and their analysis. My personal aim for my Master’s studies is to learn how to interpret LLM behavior from the perspective of linguistics and psycholinguistics.</p>
  <p>Earlier, I worked as a Natural Language Processing engineer in Yandex, developing state-of-the-art LLMs for the Russian language. I also have research experience from internships in Tinkoff AI and Computational Pragmatics Lab at HSE.</p>
  <p>Currently, I am looking for a position of research assistant at Saarbrücken, so please let me know if you are hiring!</p>
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