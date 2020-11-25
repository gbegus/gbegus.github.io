---
layout: post
title: New preprint out on CNNs, iterative learning & language change. 
date: 2020-11-25
inline: false
---

New preprint out on CNNs, iterative learning & language change. 

[arXiv preprint](https://arxiv.org/abs/2011.05463)

Can we model cultural evolution of language with deep convolutional nets?

The paper proposes a framework for modeling soundchange that combines deep convolutional neural networks and iterative learning.

GANs generate innovative outputs that are highly informative. Imperfect learning can accumulate in what appears like a language change.

Four generations of GANs were trained on an allophonic distribution in English where voiceless stops are aspirated except if preceded by [s].

The first generation of networks is trained on the relevant sequences in human speech from TIMIT. The subsequent generations are not trained on TIMIT, but on generated outputs from the previous generation and thus start learning from each other in an iterative learning task.

The initial allophonic distribution is progressively being lost with each generation, likely due to pressures from the global distribution of aspiration in the training data that resembles phonological pressures in natural language.

The networks show signs of a gradual shift in phonetic targets characteristic of a gradual phonetic sound change. At endpoints, the networks’ outputs superficially resemble a phonological change —- rule loss -— driven by imperfect #learning.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/iterat.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    CNNs in iterative learning result in language change.
</div>
