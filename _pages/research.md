---
layout: page
permalink: /research/
title: research
nav: true
nav_order: 1
---

<!-- Research page with automatic publication filtering -->

## Neural Network Theory

I study the theoretical foundations of neural networks, exploring how learning algorithms shape representations and how network architecture affects computational capacity. This work bridges machine learning theory with neuroscience to understand both artificial and biological learning systems.

<div class="publications">
  {% bibliography --query @*[keywords ~= neural-networks] %}
</div>

---

## Neuromodulation and Cellular Diversity

My research investigates how neuromodulatory systems shape neural computation and how cellular diversity contributes to brain function. I'm particularly interested in how different cell types and neuromodulatory states affect learning and memory.

<div class="publications">
  {% bibliography --query @*[keywords ~= neuromodulation] %}
</div>

---

## Computational Neuroscience

I develop computational models to understand how neural circuits process information and implement learning algorithms. This includes work on biologically plausible learning rules, neural coding principles, and the relationship between structure and function in neural networks.

<div class="publications">
  {% bibliography --query @*[keywords ~= computational-neuroscience] %}
</div>

---

## Machine Learning for Neuroscience

I create and apply machine learning tools to analyze neural data, particularly single-cell datasets. This work focuses on developing methods that can handle the scale and complexity of modern neuroscience data while providing interpretable insights into brain function.

<div class="publications">
  {% bibliography --query @*[keywords ~= machine-learning] %}
</div>

---

## Systems Neuroscience

I study how neural systems implement computations across multiple scales, from single neurons to brain-wide networks. This includes experimental and theoretical work on how neural representations emerge from network dynamics and learning.

<div class="publications">
  {% bibliography --query @*[keywords ~= systems-neuroscience] %}
</div>