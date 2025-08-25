---
permalink: /
author_profile: true
redirect_from: 
  - /about/
---

<div class="about-me">
  <h1>About Me</h1>
  <p>Hi, I'm Mark! 👋</p>
  <p>I am about to start my PhD at EPFL, where I'll be part of the <a href="https://www.epfl.ch/labs/tml/">Theory of Machine Learning Lab</a>, advised by Prof. Nicolas Flammarion. Previously, I completed my Master's at Saarland University, where I worked with <a href="https://lacoco-lab.github.io/home/">Prof. Michael Hahn</a>.</p>
  <p>I am amazed by the unreasonable effectiveness of Deep Learning. Somehow, it seems that you can get incredibly capable models by throwing data at gradient descent at large scale (plus a lot of engineering). This felt like magic to me when I first started studying ML, and it still does. Seeing through the spell is the main goal of my research: I want to understand how neural networks (and especially LLMs, which are arguably the most impressive class of them) work so well.</p>
  <p>Speaking more concretely, I am currently interested in expressivity <i>(what can models learn in principle?)</i>, interpretability <i>(what do they learn in practice?)</i>, and training dynamics <i>(how and why do they learn that?)</i>. Two recent projects in this spirit that I worked on: <a href="https://arxiv.org/abs/2502.02393">one</a> on the limits of Chain-of-Thought expressivity, and <a href="https://openreview.net/pdf?id=lniwJxd2cT">another</a> on the mechanisms of feature development in LLMs.
  </p>
  <hr>
  <p>When I'm not staring at my Weights & Biases dashboards, I enjoy a range of (rather stereotypical) hobbies, such as reading books, traveling by train, bike, and on foot, or playing board games. Recently I also got into trail running, and I'm very excited about challenging myself on the alpine trails of Switzerland.
  </p>
  <p>I'm always happy to meet new friends and collaborators! Feel free to drop me an email or message me on X about anything, and if you're in Lausanne, let's grab coffee ☕️☕️
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