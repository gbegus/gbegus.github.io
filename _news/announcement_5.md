---
layout: post
title: I'll give a talk at MIT BCS Comp Lang
date: 2020-09-15
inline: false
---

Tuesday, September 22, at 5pm EDT (2pm Pacific) over Zoom.

**Modeling Language with Generative Adversarial Networks**

In this talk, I argue that speech acquisition can be modeled with deep convolutional networks within the Generative Adversarial Networks framework. A proposed technique for retrieving internal representations that are phonetically or phonologically meaningful (Beguš 2020) allows us to model several processes in speech and compare outputs of the models both behaviorally as well as in terms of representation learning. The networks not only represent phonetic units with discretized representations (resembling the phonemic level), but also learn to encode phonological processes (resembling rule-like computation). I further propose an extension of the GAN architecture in which learning of meaningful linguistic units emerges from a requirement that the networks output informative data. I briefly present five case studies (allophonic learning, lexical learning, reduplication, iterative learning, and artificial grammar experiments) and argue that correspondence between single latent variables and meaningful linguistic content emerges. The key strategy to elicit the underlying linguistic values of latent variables is to manipulate them well outside of the training range; this allows us to actively force desired features in the output and test what types of dependencies deep convolutional networks can and cannot learn.

The advantage of this proposal is that speech acquisition is modeled in an unsupervised manner from raw acoustic data and that deep convolutional networks output not replicated, but innovative data. These innovative outputs are structured, linguistically interpretable, and highly informative. Training networks on speech data thus not only informs models of language acquisition, but also provides insights into how deep convolutional networks learn internal representations. I will also make a case that higher levels of representation such as morphology, syntax and lexical semantics can be modeled from raw acoustic data with this approach and outline directions for further experiments.