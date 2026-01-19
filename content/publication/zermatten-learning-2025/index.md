---
title: Learning transferable land cover semantics for open vocabulary interactions
  with remote sensing images
authors:
- Valérie Zermatten
- Javiera Castillo-Navarro
- Diego Marcos
- Devis Tuia
date: '2025-02-01'
publishDate: '2026-01-19T20:02:20.449945Z'
publication_types:
- article-journal
doi: 10.1016/j.isprsjprs.2025.01.006
abstract: 'Why should we confine land cover classes to rigid and arbitrary definitions?
  Land cover mapping is a central task in remote sensing image processing, but the
  rigorous class definitions can sometimes restrict the transferability of annotations
  between datasets. Open vocabulary recognition, i.e. using natural language to define
  a specific object or pattern in an image, breaks free from predefined nomenclature
  and offers flexible recognition of diverse categories with a more general image
  understanding across datasets and labels. The open vocabulary framework opens doors
  to search for concepts of interest, beyond individual class boundaries. In this
  work, we propose to use Text As supervision for COntrastive Semantic Segmentation
  (TACOSS), and we design an open vocabulary semantic segmentation model that extends
  its capacities beyond that of a traditional model for land cover mapping: In addition
  to visual pattern recognition, TACOSS leverages the common sense knowledge captured
  by language models and is capable of interpreting the image at the pixel level,
  attributing semantics to each pixel and removing the constraints of a fixed set
  of land cover labels. By learning to match visual representations with text embeddings,
  TACOSS can transition smoothly from one set of labels to another and enables the
  interaction with remote sensing images in natural language. Our approach combines
  a pretrained text encoder with a visual encoder and adopts supervised contrastive
  learning to align the visual and textual modalities. We explore several text encoders
  and label representation methods and compare their abilities to encode transferable
  land cover semantics. The model’s capacity to predict a set of different land cover
  labels on an unseen dataset is also explored to illustrate the generalization capacities
  across domains of our approach. Overall, TACOSS is a general method and permits
  adapting between different sets of land cover labels with minimal computational
  overhead. Code is publicly available online11https://github.com/eceo-epfl/RS-OVSS..'
tags:
- Land cover mapping
- Open vocabulary semantic segmentation
- Vision-language model for remote sensing
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0924271625000061
---
