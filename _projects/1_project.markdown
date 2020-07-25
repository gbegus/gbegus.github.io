---
layout: page
title: Generative Adversarial Phonology
description: Deep learning models in phonology
img: /assets/img/12.jpg
importance: 2
---


 
Training deep NNs on speech data can provide valuable insights for neural network interpretability & for modeling language acquisition.
The paper *Generative Adversarial Phonology* argues that phonetic and phonological learning can be modeled as a dependency between latent space and generated data in in Generative Adversarial Networks & in general that language acquisition can be modeled with GANs.
A technique to identify latent variables that correspond to phonetic/phonological representations is proposed. Manipulating a single variable results in [s] being forced in or out of the output.
GANs generate innovative outputs that can be directly compared to stages in language acquisition. E.g. Generator learns the aspiration rule in English, but imperfectly so: occasionally it outputs innovative long aspiration "spha" sequences, parallel to L1 & L2 acquisition (see video).

<iframe width="420" height="315" src="https://youtube.com/embed/7V6-swxAs_s" frameborder="0" allowfullscreen></iframe>



* [Paper in *Frontiers in AI*](https://www.frontiersin.org/articles/10.3389/frai.2020.00044/full)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/12.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Fiwgan architecture.
</div>

Can neural networks learn to produce outputs that resemble human speech? What learning mechanisms do neural networks use and how is their learning similar and different from phonological acquisition in human infants? We address these questions by training a Generative Adversarial Network on an allophonic alternation in English. The Generative Adversarial architecture uniquely resembles unsupervised learning of human speech because it involves two neural networks, the Generator and the Discriminator, that act in a similar way to the production-perception loop in speech acquisition. The Generator learns to produce speech-like outputs from random noise. The Discriminator learns to distinguish Generator’s outputs from real data. In time, the Generator starts producing data such that the Discriminator is inaccurate in distinguishing them from real data. 

