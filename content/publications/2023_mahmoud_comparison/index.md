---
title: A Comparison of Mutual Information, Linear Models and Deep Learning Networks for Protein Secondary Structure Prediction

authors:
- Saida SM Mahmoud
- Beatrice Portelli
- Giovanni D'Agostino
- Gianluca Pollastri
- Giuseppe Serra
- Federico Fogolari

date: '2023-07-03'
publishDate: '2025-03-08T19:22:30.674741Z'

publication_types:
- article-journal

publication: '*Current Bioinformatics*'
doi: "http://dx.doi.org/10.2174/1574893618666230417103346"

abstract: |
  Background: Over the last several decades, predicting protein structures from amino acid sequences has been a core task in bioinformatics. Nowadays, the most successful methods employ multiple sequence alignments and can predict the structure with excellent performance. These predictions take advantage of all the amino acids at a given position and their frequencies. However, the effect of single amino acid substitutions in a specific protein tends to be hidden by the alignment profile. For this reason, single-sequence-based predictions attract interest even after accurate multiple-alignment methods have become available: the use of single sequences ensures that the effects of substitution are not confounded by homologous sequences.

  Objective: This work aims at understanding how the single-sequence secondary structure prediction of a residue is influenced by the surrounding ones. We aim at understanding how different prediction methods use single-sequence information to predict the structure.
  
  Methods: We compare mutual information, the coefficients of two linear models, and three deep learning networks. For the deep learning algorithms, we use the DeepLIFT analysis to assess the effect of each residue at each position in the prediction.
  
  Results: Mutual information and linear models quantify direct effects, whereas DeepLIFT applied on deep learning networks quantifies both direct and indirect effects.
  
  Conclusion: Our analysis shows how different network architectures use the information of single protein sequences and highlights their differences with respect to linear models. In particular, the deep learning implementations take into account context and single position information differently, with the best results obtained using the BERT architecture.

featured: false

---
