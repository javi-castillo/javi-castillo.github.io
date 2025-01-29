---
title: What to align in multimodal contrastive learning?
authors:
- admin
- Benoit Dufumier
- Devis Tuia
- Jean-Philippe Thiran
date: '2025-01-01'
publishDate: '2024-12-29T17:27:10.766338Z'
publication_types:
- manuscript
publication: International Conference on Learning Representations
doi: 10.48550/arXiv.2409.07402
abstract: 'Humans perceive the world through multisensory integration, blending the
  information of different modalities to adapt their behavior. Contrastive learning
  offers an appealing solution for multimodal self-supervised learning. Indeed, by
  considering each modality as a different view of the same entity, it learns to align
  features of different modalities in a shared representation space. However, this
  approach is intrinsically limited as it only learns shared or redundant information
  between modalities, while multimodal interactions can arise in other ways. In this
  work, we introduce CoMM, a Contrastive Multimodal learning strategy that enables
  the communication between modalities in a single multimodal space. Instead of imposing
  cross- or intra- modality constraints, we propose to align multimodal representations
  by maximizing the mutual information between augmented versions of these multimodal
  features. Our theoretical analysis shows that shared, synergistic and unique terms
  of information naturally emerge from this formulation, allowing us to estimate multimodal
  interactions beyond redundancy. We test CoMM both in a controlled and in a series
  of real-world settings: in the former, we demonstrate that CoMM effectively captures
  redundant, unique and synergistic information between modalities. In the latter,
  CoMM learns complex multimodal interactions and achieves state-of-the-art results
  on the six multimodal benchmarks.'

links:
- name: arXiv
  url: http://arxiv.org/abs/2409.07402

featured: true

url_pdf: 'http://arxiv.org/pdf/2409.07402'
url_code: 'https://github.com/Duplums/align_or_not'
url_dataset: 'https://github.com/pliang279/MultiBench'

image:
  focal_point: ""
  preview_only: false

tags:
- Multimodal learning
- Representation learning
- Contrastive learning
---
