---
layout: post
date: 2020-10-26
title: How to combine human behavioral experiments and CNNs? A new preprint is on arXiv
inline: false
---

GANs output linguistically informative results even when trained on extremely small datasets. 

This means we can compare learning in human behavioral experiments and deep CNN trained on the same data. 

Preprint: [arXiv](https://arxiv.org/abs/2009.12711).

The paper proposes a technique to follow how the network searches through the space of possible sound combinations and uses linguistically interpretable strategies when learning. 

Spectrograms below show how the network transforms outputs as training progresses.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/spec1.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Generated outputs.
</div>

Appearance of rule-like computational emerges in deep convolutional nets as an interaction between latent variables. Spectrograms below illustrate vowel harmony when 2 latent variables are manipulated.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/spec2.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
     Generated outputs.
</div>