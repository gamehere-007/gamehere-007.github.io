---
title: "Z Lab - Research"
layout: textlay
excerpt: "Z Lab -- Research"
sitemap: false
permalink: /research/
---

# RESEARCH

---

#### **Scientific Machine Learning for Engineered Systems**
<!-- Faced with a fundamental shift in both complexity and volume of the data, scientists have been struggling in finding ways to automate both analyses, and possibly the interpretation of the datasets.  Machine Learning is a rapidly evolving field that has proven to be extremely efficient in solving challenges in multiple domains including signal processing, vision, self-driving, gaming, health and robotics. One may ask whether we can leverage the advances in machine learning and statistics for science. Our group specializes in applying and developing novel methods in machine learning on astrophysical challenges. -->

Machine learning and deep learning are rapidly growing fields that learn representations of data via computational models, which have proven to successfully solve challenges in multiple domains. One emerging question is whether we can bridge deep learning methods with engineering and science, where models are commonly derived based on physical laws. Our group is particularly interested in developing and applying novel approaches in machine learning/deep learning for challenges in dynamical systems and engineered systems.

<!-- ![alt text]({{ site.url }}{{ site.baseurl }}/images/respic/intro.png ){ width=50% } -->



<!-- <figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/intro.png" alt="drawing" style="width: 800px">
</figure> -->

<p align="center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/intro_new.png" alt="drawing" style="width: 85%;">
</p>


**Relevant Research:**

[[discovering governing equations]](https://www.sciencedirect.com/science/article/pii/S0888327018305727)

[[structural damage detection 1]](https://doi.org/10.1002/stc.2306)
[[structural damage detection 2]](https://doi.org/10.1016/j.measurement.2016.04.016)

[[discrepancy modeling via Neural ODEs]](https://www.sciencedirect.com/science/article/pii/S0022460X21002686)
[[PgDMM]](https://arxiv.org/abs/2110.08607)

---

#### **Vision-based Sensing for Structural Monitoring**

Sensing technologies have emerged as aided tools or solutions for continuously measuring data from systems either for the purpose of monitoring or system characterization. In this direction, the group's research works have been exploiting the solutions for easily deployed, low costing, and data-efficient sensing.

<p align="center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/event.gif" alt="drawing" style="width: 40%;"> &nbsp;
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/event2.png" alt="drawing" style="width: 55%;">
</p>

**Relevant Research:**

[[full-field motion tracking via event-based cameras]](https://www.sciencedirect.com/science/article/pii/S0888327020302910)

[[tracking continuous edge from videos]](https://doi.org/10.1016/j.ymssp.2020.106847)

#### **Mobility Sensing (Ongoing)**

This research  investigates the possibility of shifting the sensing paradigm from a stationary manner to a mobile manner, which has the potential of increasing the spatial resolution of sensing, and of benefiting the sensing for city-scale applications.

<p align="center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/MS.png" alt="drawing" style="width: 85%;">
</p>

<p align="center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/MS2.png" alt="drawing" style="width: 50%;">
</p>


#### **and More is coming...**



---

# PUBLICATIONS

(For a full list of publications, go to [Google Scholar](https://scholar.google.com/citations?user=LuwuuVQAAAAJ&hl=en&authuser=1))

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}



<!-- ### ... and more. -->
