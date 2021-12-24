---
title: "Z Lab - Research"
layout: textlay
excerpt: "Z Lab -- Research"
sitemap: false
permalink: /research/
---

# Research
* <font color="blue"> Scientific Machine Learning for Engineered Systems </font>
<!-- Faced with a fundamental shift in both complexity and volume of the data, scientists have been struggling in finding ways to automate both analyses, and possibly the interpretation of the datasets.  Machine Learning is a rapidly evolving field that has proven to be extremely efficient in solving challenges in multiple domains including signal processing, vision, self-driving, gaming, health and robotics. One may ask whether we can leverage the advances in machine learning and statistics for science. Our group specializes in applying and developing novel methods in machine learning on astrophysical challenges. -->

Machine learning and deep learning are rapidly growing fields that learn representations of data via computational models, which have proven to successfully solve challenges in multiple domains. One emerging question is whether we can bridge the advanced in deep learning with engineering and science, where models are commonly derived based on physical laws. Our group is particularly interested in developing and applying novel approaches in machine learning/deep learning for challenges in dynamical systems and engineered systems.

<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/intro.png" style="width: 800px">
</figure>


**Relevent research:**

[[discovering governing equations]](https://www.sciencedirect.com/science/article/pii/S0888327018305727)
[[discrepany modeling via Neural ODEs]](https://www.sciencedirect.com/science/article/pii/S0022460X21002686)
[[PgDMM]](https://arxiv.org/abs/2110.08607)

* <font color="blue"> Vision-based Sensing for Structural Monitoring </font>

[[full-field motion tracking via event-based cameras]](https://www.sciencedirect.com/science/article/pii/S0888327020302910)
[[tracing continuous edge from videos]](https://doi.org/10.1016/j.ymssp.2020.106847)

# and more ...


# Selected Publications

(For a full list of publications, go to [Google Scholar](https://scholar.google.ch/citations?user=LuwuuVQAAAAJ&hl=en&authuser=1))

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}



<!-- ### ... and more. -->
