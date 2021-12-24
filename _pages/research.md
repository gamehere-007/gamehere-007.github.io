---
title: "Z Lab - Research"
layout: textlay
excerpt: "Z Lab -- Research"
sitemap: false
permalink: /research/
---

# Research
* **Scientific Machine Learning for Engineered Systems**
<!-- Faced with a fundamental shift in both complexity and volume of the data, scientists have been struggling in finding ways to automate both analyses, and possibly the interpretation of the datasets.  Machine Learning is a rapidly evolving field that has proven to be extremely efficient in solving challenges in multiple domains including signal processing, vision, self-driving, gaming, health and robotics. One may ask whether we can leverage the advances in machine learning and statistics for science. Our group specializes in applying and developing novel methods in machine learning on astrophysical challenges. -->

Machine learning and deep learning are rapidly growing fields that learn representations of data via computational models, whihc have proven to successully solve challenges in multiple domains. One emerging question is whether we can bridge the adavanced in deep learning with engineering and science, where models are commonly derived based on physcal laws. Our group is particularly intrested in developing and applying novel approaches in machine learning/deep learning for challenges in dynamical systems and engineered systems.


Relevent research:




* **Vision-based Sensing for Structural Monitoring**


# Selected Publications

(For a full list of publications, go to [Google Scholar](https://scholar.google.ch/citations?user=LuwuuVQAAAAJ&hl=en&authuser=1))

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}



<!-- ### ... and more. -->
