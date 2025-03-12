---
title: 'DiLBERT: Cheap Embeddings for Disease Related Medical NLP'

authors:
- Kevin Roitero
- Beatrice Portelli
- Mihai Horia Popescu
- Vincenzo Della Mea

date: "2021-11-30"
publishDate: '2025-03-08T19:22:30.589277Z'

tags:
- health
- NLP

publication_types:
- article-journal

publication: '*IEEE Access*'
doi: "https://doi.org/10.1109/ACCESS.2021.3131386"

abstract: |
  Electronic Health Records include health-related information, among which there is text mentioning health conditions and diagnoses. Usually, text is also coded using appropriate terminologies and classifications. The act of coding is time consuming and prone to mistakes. Consequently, there is increasing demand for clinical text mining tools to help coding. In last few years Natural Language Processing (NLP) models has been shown to be effective in sentence-level tasks. Taking advantage from the transfer learning capabilities of those models, a number of biomedicine and health specific models have been also developed. However, also biomedical models can be seen as too general for some specific area like diagnostic expressions. In this paper, we describe a BERT model specialized on tasks related to diagnoses and health conditions. To obtain a disease-related language model, we created a pre-training corpora starting from ICD-11 entities, and enriched them with documents selected by querying PubMed and Wikipedia with entity names. Fine-tuning has been carried out towards three downstream tasks on two different datasets. Results show that our model, besides being trained on a much smaller corpora than state-of-the-art algorithms, leads to comparable or higher accuracy scores on all the considered tasks, in particular 97.53% accuracy on death certificate coding, and 81.32% on clinical document coding, which are both slightly higher than other models. To summarize the practical implications of our work, we pre-trained and fine-tuned a domain specific BERT model on a small corpora, with comparable or better performance than state-of-the-art models. This approach may also simplify the development of models for languages different from English, due to the minor quantity of data needed for training.

featured: false

---
