---
title: 'ConGeo: Robust Cross-View Geo-Localization Across Ground View Variations'
authors:
- Li Mi
- Chang Xu
- admin
- Syrielle Montariol
- Wen Yang
- Antoine Bosselut
- Devis Tuia
date: '2024-09-29'
publishDate: '2024-12-29T17:29:25.090997Z'
publication_types:
- paper-conference
publication: 'European Conference on Computer Vision (ECCV)'
doi: 10.1007/978-3-031-72630-9_13
abstract: 'Cross-view geo-localization aims at localizing a ground-level query image
  by matching it to its corresponding geo-referenced aerial view. In real-world scenarios,
  the task requires accommodating diverse ground images captured by users with varying
  orientations and reduced field of views (FoVs). However, existing learning pipelines
  are orientation-specific or FoV-specific, demanding separate model training for
  different ground view variations. Such models heavily depend on the North-aligned
  spatial correspondence and predefined FoVs in the training data, compromising their
  robustness across different settings. To tackle this challenge, we propose ConGeo,
  a single- and cross-view Contrastive method for Geo-localization: it enhances robustness
  and consistency in feature representations to improve a model’s invariance to orientation
  and its resilience to FoV variations, by enforcing proximity between ground view
  variations of the same location. As a generic learning objective for cross-view
  geo-localization, when integrated into state-of-the-art pipelines, ConGeo significantly
  boosts the performance of three base models on four geo-localization benchmarks
  for diverse ground view variations and outperforms competing methods that train
  separate models for each ground view variation.'


links:
- name: URL
  url: https://eceo-epfl.github.io/ConGeo/
url_pdf: https://arxiv.org/pdf/2403.13965
url_code: https://github.com/eceo-epfl/ConGeo
url_poster: ''

tags:
- Geo-localization
- Contrastive learning
---
