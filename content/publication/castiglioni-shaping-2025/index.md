---
title: 'Shaping Fine-Tuning of Geospatial Foundation Models: Effects of Label Availability
  and Temporal Resolution'
authors:
- Giovanni Castiglioni
- Nicolás Isla Fernández
- Cristian Buc Calderon
- Javiera Castillo Navarro
- Sébastien Lefèvre
- Valentin Barriere
date: '2025-07-17'
publishDate: '2026-01-19T20:02:20.442465Z'
publication_types:
- paper-conference
abstract: 'Fine-tuning foundation models is a key step in adapting them to a particular
  task. In the case of Geospatial Foundation Models (GFMs), fine-tuning can be particularly
  challenging given data scarcity both in terms of the amount of labeled data and,
  in the case of Satellite Image Time Series (SITS), temporal context. Under these
  circumstances, the optimal GFM fine-tuning strategy across different labeled data
  regimes remains poorly understood. In this paper, we thoroughly assess and study
  the performances of two different GFMs given several combinations of two data scarcity
  factors: the number of labeled samples and the sequence length. Specifically, we
  analyze the performances on a crop classification task, particularly, semantic segmentation
  of the Sentinel-2 images contained in the PASTIS-HD dataset. We compare GFMs to
  U-TAE, as a fully supervised baseline, across varying amounts of labeled data (1%,
  10%, 50%, 100%) and temporal input lengths (1, 6, 15, 25 and 35). Among these explorations,
  we find that using a smaller learning rate for the pre-trained encoders improves
  performance in moderate and high data regimes (50%-100%). In contrast, full fine-tuning
  outperforms partial fine-tuning in very low-label settings (1%-10%). This behavior
  suggests a nuanced trade-off between feature reuse and adaptation that defies the
  intuition of standard transfer learning.'
links:
- name: URL
  url: https://openreview.net/forum?id=CLTEaA2mtC&noteId=CLTEaA2mtC
---
