---
layout: post
title: New paper in Neural Networks":" deep neural network learns to produce new words
date: 2020-04-18
inline: false
---

The paper proposes two neural network architectures (fiwGAN and ciwGAN)  to model unsupervised learning of spoken words from raw audio and proposes a new latent space structure that can model featural learning and allows for a very low-dimension vector representation of lexical items.

* [The paper in *Neural Networks*](https://www.sciencedirect.com/science/article/pii/S0893608021001052)
* [Github code](https://github.com/gbegus/fiwGAN-ciwGAN)

The proposed network generates innovative outputs that are linguistically interpretable and highly informative. fiwGAN network trained on *suit* and *dark* outputs innovative *start*, even though it never saw *start* or even a [st] sequence in the training data (audio sample below).


<iframe width="520" height="415" src="https://youtube.com/embed/ifxjgmyuRXw" frameborder="0" allowfullscreen></iframe>

We also argue that setting latent featural codes to values well beyond training range results in almost categorical generation of prototypical lexical items and reveals underlying values of each latent code.

The proposed architecture allows testing of any property of the data and probing the learned representation behind each latent code. Lexical learning emerges even when trained on the entire TIMIT database.

FiwGAN allows very low dimension vector representation (13 binary latent variables) of lexical items when trained on TIMIT (~6k lexical items, 55k tokens). Approx. 40% of tested codes have a distinct and easily identifiable lexical item (spectrograms below).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/timit.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Generated outputs and human recordings. 
</div>
