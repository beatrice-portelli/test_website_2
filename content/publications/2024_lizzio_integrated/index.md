---
title: Integrated Encoding and Quantization to Enhance Quanvolutional Neural Networks

authors:
- daniele-lizzio-bosco
- beatrice-portelli
- giuseppe-serra

date: '2024-10-01'
publishDate: '2025-03-08T19:22:30.723806Z'

publication_types:
- article

publication: '*arXiv preprint*'
doi: "https://doi.org/10.48550/arXiv.2410.05777"

abstract: "Image processing is one of the most promising applications for quantum machine learning (QML). Quanvolutional Neural Networks with non-trainable parameters are the preferred solution to run on current and near future quantum devices. The typical input preprocessing pipeline for quanvolutional layers comprises of four steps: optional input binary quantization, encoding classical data into quantum states, processing the data to obtain the final quantum states, decoding quantum states back to classical outputs. In this paper we propose two ways to enhance the efficiency of quanvolutional models. First, we propose a flexible data quantization approach with memoization, applicable to any encoding method. This allows us to increase the number of quantization levels to retain more information or lower them to reduce the amount of circuit executions. Second, we introduce a new integrated encoding strategy, which combines the encoding and processing steps in a single circuit. This method allows great flexibility on several architectural parameters (e.g., number of qubits, filter size, and circuit depth) making them adjustable to quantum hardware requirements. We compare our proposed integrated model with a classical convolutional neural network and the well-known rotational encoding method, on two different classification tasks. The results demonstrate that our proposed model encoding exhibits a comparable or superior performance to the other models while requiring fewer quantum resources."

featured: false


---
