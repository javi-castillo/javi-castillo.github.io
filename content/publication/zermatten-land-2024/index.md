---
title: Land Cover Mapping From Multiple Complementary Experts Under Heavy Class Imbalance
authors:
- Valerie Zermatten
- Xiaolong Lu
- admin
- Tobias Kellenberger
- Devis Tuia
date: '2024-01-01'
publishDate: '2024-12-29T17:29:25.143140Z'
publication_types:
- article-journal
doi: 10.1109/JSTARS.2024.3369876
publication: IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing
abstract: Deep learning has emerged as a promising avenue for automatic mapping, demonstrating
  high efficacy in land cover categorization through various semantic segmentation
  models. Nonetheless, the practical deployment of these models encounters important
  challenges from the imbalanced distribution of samples between the classes, a problem
  inherent to real-world datasets. This results in models biased towards frequent
  classes that perform poorly on rare classes. While existing approaches to fight
  class imbalance mainly focus on image classification, here we propose to address
  this issue for semantic segmentation with a multiple complementary experts (MCE)
  structure. Taking inspiration from ensemble models, each expert in our MCE specializes
  in certain classes and works with other experts in a complementary manner to generate
  robust predictions for rare classes. We compare our approach to other existing methods
  and also explore different logit aggregation methods, to identify the performance
  upper bounds and improvement directions. Our model is evaluated on a large-scale
  and challenging alpine land cover dataset that we make openly available. In addition,
  we evaluated our model on an imbalanced land cover mapping dataset, FLAIR, to highlight
  its adaptability. Overall, our MCE model yields notable improvement in performances
  on the medium and rare classes compared to baseline methods, while only slightly
  compromising on the overall accuracy. Despite its simplicity, the MCE approach stands
  as a practical solution for more operational semantic segmentation models, not trading
  off performances on rare but important classes.
tags:
- Class imbalance
- Land cover mapping
- Mixture of experts
- Earth observation
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10444917
---
