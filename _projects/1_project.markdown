---
layout: page
title: Generative Adversarial Phonology
description: Deep learning models in phonology
img: /assets/img/12.jpg
importance: 1
---

Can neural networks learn to produce outputs that resemble human speech? What learning mechanisms do neural networks use and how is their learning similar and different from phonological acquisition in human infants? We address these questions by training a Generative Adversarial Network on an allophonic alternation in English. The Generative Adversarial architecture uniquely resembles unsupervised learning of human speech because it involves two neural networks, the Generator and the Discriminator, that act in a similar way to the production-perception loop in speech acquisition. The Generator learns to produce speech-like outputs from random noise. The Discriminator learns to distinguish Generator’s outputs from real data. In time, the Generator starts producing data such that the Discriminator is inaccurate in distinguishing them from real data. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/12.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Fiwgan architecture.
</div>

