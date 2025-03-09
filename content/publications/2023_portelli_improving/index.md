---
title: Improving Multi-lingual Medical Term Normalization to Address the Long-Tail Problem

authors:
- Beatrice Portelli
- Simone Scaboro
- Giuseppe Serra

date: '2023-12-01'
publishDate: '2025-03-08T19:22:30.687195Z'

publication_types:
- paper-conference

publication: '*Proceedings of the 37th Pacific Asia Conference on Language, Information and Computation*'
publication_short: "*PACLIC 2023*"
doi: "https://aclanthology.org/2023.paclic-1.81/"

abstract: |
  Medical term normalization involves the mapping of text to specific medical terms within a medical ontology. However, due to the vast number of possible medical terms and the scarcity of annotated datasets, this task becomes particularly challenging, especially for languages other than English, where the problem is further amplified. In this paper, we propose an approach to tackle this challenge by experimenting with the ontology pre-training (OP) method. We explore its potential for generalization across multiple languages. The core of this method lies in utilizing a large medical ontology, such as MedDRA, to generate synthetic samples in various languages to use during the model’s pre-training. This augmentation technique aims to enhance the model’s ability to generalize to classes that were not encountered during the fine-tuning process. To assess the effectiveness of our approach, we compare the performance of a robust zero-shot multilingual model with traditional fine-tuning, ontology pre-training, and their combined strategies. We experiment on three datasets for medical entity normalization belonging to different languages (English, French, and Russian), and analyze the effect of the presence/absence of the target language in the pre-training step. The results demonstrate the successful extension of ontology pre-training to multiple languages. We observe that multi-language pretraining significantly improves the baseline performance of models, enabling them to achieve strong performance without any loss when finetuned on new languages.

featured: false

---
