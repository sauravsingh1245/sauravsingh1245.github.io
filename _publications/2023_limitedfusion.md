---
title: "Multimodal aerial view object classification with disjoint unimodal feature extraction and fully-connected-layer fusion"
collection: SPIE Digital Library
permalink: /publication/2023_limitedfusion
excerpt: 'This paper presents a two-phase multi-stream fusion approach for training networks with limited multimodal data, addressing the challenges of collecting paired data and demonstrating improved performance on the NTIRE-21 dataset.'
date: 2023-06-13
venue: 'Big Data V: Learning, Analytics, and Applications, SPIE, 2023'
paperurl: 'http://sauravsingh1245.github.io/files/2023_limitedfusion.pdf'
slidesurl: 'http://sauravsingh1245.github.io/files/2023_limitedfusion_Slides.pdf'
citation: 'S. Singh, M. Sharma, J. Heard, J. D. Lew, E. Saber, and P. P. Markopoulos, “Multimodal aerial view object classification with disjoint
unimodal feature extraction and fully-connected-layer fusion,” in Big Data V: Learning, Analytics, and Applications, vol. 12522, p. 1252206,
SPIE, 2023.'
---
Fusion of multimodal data can offer enhanced machine learning. One of the most common fusion approaches in deep learning is end-to-end training of a neural network on all available modalities. However, paired multimodal data from all the modalities is required to train such a network. Collecting paired data from multiple modalities can be challenging and expensive due to the requirement of specialized equipment, atmospheric conditions, limitation of individual modalities to probe a scene, data integration from modalities with different spatial and spectral resolutions, and annotation challenges for obtaining ground truth. A two-phase multi-stream fusion approach is presented in this work to counteract this issue. First, we train the unimodal streams in parallel with their own decision layers, loss, and hyper-parameters. Then, we discard the individual decision layers, concatenate the last feature map of all unimodal streams, and jointly train a common multimodal decision layer. We tested the proposed approach on the NTIRE-21 dataset. Our experiments corroborate that in multiple cases, the proposed method can outperform the alternatives.
![Multimodal fusion network.](\../images/multimodal.png)