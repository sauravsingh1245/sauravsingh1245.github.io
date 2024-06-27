---
title: "Spatial and Temporal Attention-based emotion estimation on HRI-AVC dataset"
collection: IEEE Xplore
permalink: /publication/2023_emotion_net
excerpt: 'This paper introduces the HRI-AVC dataset, featuring self-reported emotional measures from human-robot interactions, and proposes an attention-based network for estimating human emotion through arousal and valence from image frames in real-time.'
date: 2023-10-01
venue: '2023 IEEE International Conference on Systems, Man, and Cybernetics (SMC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10394066'
citation: 'K. Subramanian, S. Singh, J. Namba, J. Heard, C. Kanan, and F. Sahin, "Spatial and Temporal Attention-Based Emotion Estimation on HRI-AVC Dataset," 2023 IEEE International Conference on Systems, Man, and Cybernetics (SMC), Honolulu, Oahu, HI, USA, 2023, pp. 4895-4900, doi: 10.1109/SMC53992.2023.10394066.'
---
Many attempts have been made at estimating discrete emotions (calmness, anxiety, boredom, surprise, anger) and continuous emotional measures commonly used in psychology, namely valence (The pleasantness of the emotion being displayed) and arousal (The intensity of the emotion being displayed). Existing methods to estimate arousal and valence rely on learning from data sets, where an expert annotator labels every image frame. Access to an expert annotator is not always possible, and the annotation can also be tedious. Hence it is more practical to obtain self-reported arousal and valence values directly from the human in a real-time Human-Robot collaborative setting. Hence this paper provides an emotion data set (HRI-AVC) obtained while conducting a human-robot interaction (HRI) task. The self-reported pair of labels in this data set is associated with a set of image frames. This paper also proposes a spatial and temporal attention-based network to estimate arousal and valence from this set of image frames. The results show that an attention-based network can estimate valence and arousal on the HRI-AVC data set even when Arousal and Valence values are unavailable per frame.
![Attention-based Emotion Network architecture](\../images/aggregator_net_updated.png)