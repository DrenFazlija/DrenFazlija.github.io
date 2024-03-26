---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
## Welcome

Hi 👋,

I am **Dren**, a Ph.D. student at the L3S research center in Hannover, Germany. My research interests are basically everything covered in the Wikipedia page for [Adversarial Machine Learning](https://en.wikipedia.org/wiki/Adversarial_machine_learning). I am particularly fond of **adversarial examples** and **model stealing** 🕵️

I graduated from Leibniz University Hannover in 2022 with a master's degree in Computer Science.

Feel free to reach out if you want to discuss anything related to AI!


## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
