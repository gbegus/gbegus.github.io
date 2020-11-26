---
layout: post
title: Can deep convolutional network learn identity-based patterns? A new preprint is on arXiv
date: 2020-09-23
inline: false
---



We train a [ciwGAN](https://arxiv.org/abs/2006.02951) model on reduplication in speech (a syllable [pa] gets copied, e.g. [para] -> [pa-para]). The network learns to encode an identity-based pattern in its latent space & learns to apply it to unobserved data.

Pre-print[arXiv](https://arxiv.org/abs/2009.06110).

For example, manipulating only the latent codes, we can turn an unreduplicated output [piru] into a reduplicated one [pipiru]. Waveform below shows a gradual transition from [piru] to [pipiru] with interpolation of latent codes.

Reduplication (copying) is extended to unobserved data. [s]-initial words were never reduplicated in training. With a  proposed technique, we can force both [s] and reduplication. The network outputs [sisiji], very similar to human outputs that were withheld from training (below).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/gen.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Generated outputs and human recordings. 
</div>
