---
layout: post
title: New paper in Neural Networks: deep neural network learns to produce new words
date: 2021-04-18
inline: false
---

The paper proposes two neural network architectures (fiwGAN and ciwGAN)  to model unsupervised learning of spoken words from raw audio and proposes a new latent space structure that can model featural learning and allows for a very low-dimension vector representation of lexical items.

* [The paper in (*Neural Networks*)](https://www.sciencedirect.com/science/article/pii/S0893608021001052)
* [Github code](https://github.com/gbegus/fiwGAN-ciwGAN)

The proposed network generates innovative outputs that are linguistically interpretable and highly informative. fiwGAN network trained on *suit* and *dark* outputs innovative *start*, even though it never saw *start* or even a [st] sequence in the training data (audio sample below).
