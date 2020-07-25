---
layout: page
title: Fiwgan
description: Lexical learning in GANs
img: /assets/img/7.jpg
importance: 1
---


 
How can deep neural networks encode information that corresponds to words in human speech into raw acoustic data? This paper proposes two neural network architectures for modeling unsupervised lexical learning from raw acoustic inputs, ciwGAN (Categorical InfoWaveGAN) and fiwGAN (Featural InfoWaveGAN), that combine a DCGAN architecture for audio data (WaveGAN; arXiv:1705.07904) with InfoGAN (arXiv:1606.03657), and propose a new latent space structure that can model featural learning simultaneously with a higher level classification. The architectures introduce a network that learns to retrieve latent codes from generated audio outputs. Lexical learning is thus modeled as emergent from an architecture that forces a deep neural network to output data such that unique information is retrievable from its acoustic outputs. The networks trained on lexical items from TIMIT learn to encode unique information corresponding to lexical items in the form of categorical variables. By manipulating these variables, the network outputs specific lexical items. Innovative outputs suggest that phonetic and phonological representations learned by the network can be productively recombined and directly paralleled to productivity in human speech: a fiwGAN network trained on 'suit' and 'dark' outputs innovative 'start', even though it never saw 'start' or even a [st] sequence in the training data. We also argue that setting latent featural codes to values well beyond training range results in almost categorical generation of prototypical lexical items and reveals underlying values of each latent code. Probing deep neural networks trained on well understood dependencies in speech bears implications for latent space interpretability, understanding how deep neural networks learn meaningful representations, as well as a potential for unsupervised text-to-speech generation in the GAN framework.

<iframe width="420" height="315" src="https://youtube.com/embed/ifxjgmyuRXw" frameborder="0" allowfullscreen></iframe>



* [Github code](https://github.com/gbegus/fiwGAN-ciwGAN)
* [arXiv preprint](https://arxiv.org/abs/2006.02951)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/7.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Fiwgan architecture.
</div>



