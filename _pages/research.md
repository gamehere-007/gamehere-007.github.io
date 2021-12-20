---
title: "Z Lab - Research"
layout: textlay
excerpt: "Z Lab -- Research"
sitemap: false
permalink: /research/
---

# Research
* **Scientific Machine Learning for Dynamical Systems**



# Selected Publications

(For a full list of publications, go to [Google Scholar](https://scholar.google.ch/citations?user=LuwuuVQAAAAJ&hl=en&authuser=1))

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}



### ... and more.
