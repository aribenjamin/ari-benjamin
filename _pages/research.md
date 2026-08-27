---
layout: page
permalink: /research/
title: research
description: Neural network theory, learning dynamics and continual learning, language models, and computational neuroscience.
nav: true
nav_order: 1
---

### Why networks learn what they do

The through-line of my research is the theory of learning in neural networks: what a network will learn from data, and why. I have shown that efficient neural codes — long treated as a design principle for the brain — emerge naturally in any network trained by gradient descent, studied how to measure and regularize networks in the space of functions they compute rather than their weights, and shown that a trained network can be understood as a Bayesian ensemble of its tangent functions. That last result gives a probabilistic account of catastrophic forgetting and points toward gradient-based algorithms for continual learning. I have also studied why generalization is sometimes delayed long after the training loss falls ("grokking"), tracking how representational geometry changes during learning. I co-organized a COSYNE workshop on this theme ("Why networks learn what they do," 2023) and co-authored the published lecture notes of the Gatsby Unit's Analytical Connectionism summer school with Andrew Saxe, Jay McClelland, and colleagues.

<div class="publications">
  {% bibliography --query @*[keywords ~= neural-networks] --group_by none %}
</div>

---

### Knowledge and learning in language models

Language models raise the questions above in a new and pressing form. With Tingkai Liu and Tony Zador, I have worked on uncertainty-aware objectives for post-training language models at the token level. I am curious about how knowledge is formed and kept self-consistent in these models: what is learned in context versus in weights, how beliefs formed from one context should propagate to others, and whether the complementary-learning-systems perspective from neuroscience is the right lens for continual learning in modern AI. I think many of these questions can be understood analytically.

<div class="publications">
  {% bibliography --query @*[keywords ~= llm] --group_by none %}
</div>

---

### Neuromodulation and cellular diversity

Much of my ongoing research is about building a connectionist framework for understanding neuromodulation — for example, treating neuromodulated networks as walking a manifold of weight configurations. I am also interested in the roles that diverse cell types play in neural circuits.

<div class="publications">
  {% bibliography --query @*[keywords ~= theory] --group_by none %}
</div>

---

### Transformers for biological data

I design and train transformers end-to-end for problems in biology. In *TissueFormer* (BMC Bioinformatics, 2026), I built a transformer that extends single-cell foundation models to predict population-level phenotypes from groups of single cells while retaining single-cell resolution — applying it to predict COVID-19 severity from blood scRNA-seq and to identify cortical areas from mouse spatial transcriptomics.

<div class="publications">
  {% bibliography --query @*[keywords ~= single-cell] --group_by none %}
</div>

---

### Machine learning for neural recordings

During my PhD I worked on machine learning methods for neural data: benchmarking how well modern ML predicts neural responses, and establishing best practices for neural decoding.

<div class="publications">
  {% bibliography --query @*[keywords ~= neural-recording] --group_by none %}
</div>

---

## Past work

### Bio-inspired materials science and molecular dynamics

Before I transitioned to neuroscience, I worked on bio-inspired materials science and molecular dynamics simulations. I was interested in self-assembly and how molecular interactions can lead to complex structures. The common thread that connected these interests was looking at nature in terms of its function, as might an engineer, as well as an interest in complex systems.
<div class="publications">
  {% bibliography --query @*[keywords ~= materials-science] --group_by none %}
</div>
