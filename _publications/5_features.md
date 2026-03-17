---
title: Understanding the Emergence of Seemingly Useless Features in Next-Token Predictors"
collection: publications
excerpt: 'Trained Transformers have been shown to compute abstract features that appear redundant for predicting the immediate next token. We identify which components of the gradient signal from the next-token prediction objective give rise to this phenomenon, and we propose a method to estimate the influence of those components on the emergence of specific features. After validating our approach on toy tasks, we use it to interpret the origins of the world model in OthelloGPT and syntactic features in a small language model. Finally, we apply our framework to a pretrained LLM, showing that features with extremely high or low influence on future tokens tend to be related to formal reasoning domains such as code. Overall, our work takes a step toward understanding hidden features of Transformers through the lens of their development during training.'
date: 2026-03-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2502.02393'
citation: 'Amiri, A., Huang, X., Rofin, M. and Hahn, M., 2025. Lower Bounds for Chain-of-Thought Reasoning in Hard-Attention Transformers. arXiv preprint arXiv:2502.02393'
authors: 'Alireza Amiri, Xinting Huang, Mark Rofin, Michael Hahn.'
---