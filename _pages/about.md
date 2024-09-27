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
  <p>My primary research interest is building the high-level intuition of LLMs, as well as applying that intuition to get actionable insights. I believe that by combining theoretical and empirical methods, we can bit-by-bit construct a Theory of Everything for LLMs, uncovering the bounds of learnability, role of different layers, dynamics of information flow, and other phenomena. As training new models becomes increasingly expensive, this research will only grow in significance, potentially saving billions in compute costs. </p>
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