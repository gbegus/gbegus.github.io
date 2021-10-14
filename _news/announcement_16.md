---
layout: post
title: I will present my TACL paper on reduplication at EMNLP 2021. 
date: 2021-10-14
inline: false
---
*Paper accepted at TACL:* [link](https://arxiv.org/abs/2006.02951)

We train a ciwGAN model on reduplication in speech (a syllable [pa] gets copied, e.g. [para] -> [pa-para]). The network learns to encode an identity-based pattern in its latent space & learns to apply it to unobserved data.

For example, manipulating only the latent codes, we can turn an unreduplicated output [piru] into a reduplicated one [pipiru]. Waveform below shows a gradual transition from [piru] to [pipiru] with interpolation of latent codes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/reduplication.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Reduplication. 
</div>
Reduplication (copying) is extended to unobserved data. [s]-initial words were never reduplicated in training. With a  proposed technique, we can force both [s] and reduplication. The network outputs [sisiji], very similar to human outputs that were withheld from training.

*Abstract:*
This paper models unsupervised learning of an identity-based pattern (or copying) in speech called reduplication from raw continuous data with deep convolutional neural networks. We use the ciwGAN architecture Beguš (2021a) in which learning of meaningful representations in speech emerges from a requirement that the CNNs generate informative data. We propose a technique to wug-test CNNs trained on speech and, based on four generative tests, argue that the network learns to represent an identity-based pattern in its latent space. By manipulating only two categorical variables in the latent space, we can actively turn an unreduplicated form into a reduplicated form with no other substantial changes to the output in the majority of cases. We also argue that the network extends the identity-based pattern to unobserved data. Exploration of how meaningful representations of identity-based patterns emerge in CNNs and how the latent space variables outside of the training range correlate with identity-based patterns in the output has general implications for neural network interpretability.

