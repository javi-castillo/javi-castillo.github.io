---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<p>&nbsp;</p>

# Talks

### Semi-Supervised Semantic Segmentation in Earth Observation.
*ESA EO Φ-Week*, September 2020. [[Video]](https://youtu.be/YdU4bJGcRZQ)

### Semi-Supervised Semantic Segmentation in Earth Observation.
 *AI4Geo web-seminar. Deep learning for Remote Sensing Image Understanding*, July 2020. [[Slides]](http://javi-castillo.github.io/files/slides/AI4GEO_seminaire.pdf)

### Deep Semi-supervised Learning for Earth Observation.
*Journée Jeunes Chercheurs MACLEAN du GDR MADICS* [[website]](), December 2019. [[Slides]](http://javi-castillo.github.io/files/slides/maclean.pdf)