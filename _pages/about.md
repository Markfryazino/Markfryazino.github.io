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
  <p>I work as a research assistant at <a href="https://lacoco-lab.github.io/home/">Language, Computation and Cognition Lab</a>. We use methods ranging from Formal Language Theory to Mechanistic Interpretability to look into the black boxes of modern LLMs. </p>
  <p>My primary research interest is understanding the principles governing the behavior and performance limits of Deep Learning models, especially LLMs. What capabilities can they learn from data, and how does that happen? What inductive biases are introduced by specific architectural modifications? I believe that by combining theoretical and empirical methods, we can answer these questions, which is both interesting by itself and useful to improve our models.
   </p>
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