---
title: "Distilling Knowledge from Well-informed Soft Labels for Neural Relation Extraction"
collection: publications
permalink: /publication/2019-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2019-10-01
venue: 'AAAI2020'
paperurl: 'http://academicpages.github.io/files/KD4NER.pdf'
citation: 'Zhenyu Zhang, Xiaobo Shu, Bowen Yu, Tingwen Liu, Jiapeng Zhao, Quangang Li, Li Guo.'
---
Extracting relations from plain text is an important task with wide application. Most existing methods formulate it as a su- pervised problem and utilize one-hot hard labels as the sole target in training, neglecting the rich semantic information among relations. In this paper, we aim to explore the super- vision with soft labels in relation extraction, which makes it possible to integrate prior knowledge. Specifically, a bipartite graph is first devised to discover type constraints between en- tities and relations based on the entire corpus. Then, we com- bine such type constraints with neural networks to achieve a knowledgeable model. Furthermore, this model is regarded as teacher to generate well-informed soft labels and guide the optimization of a student network via knowledge distillation. Besides, a multi-aspect attention mechanism is introduced to help student mine latent information from text. In this way, the enhanced student inherits the dark knowledge (e.g., type constraints and relevance among relations) from teacher, and directly serves the testing scenarios without any extra con- straints. We conduct extensive experiments on the TACRED and SemEval datasets, the experimental results justify the ef- fectiveness of our approach.

[Download paper here](http://academicpages.github.io/files/KD4NER.pdf)
