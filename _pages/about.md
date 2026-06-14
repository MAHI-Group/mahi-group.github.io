---
permalink: /
title: "Machine-and-Human Intelligence Lab"
excerpt: "AI for Science at BITS Pilani, Goa."
layout: single
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

The Machine-and-Human Intelligence Lab (MAHI Lab) is a research group in the
Department of Computer Science at BITS Pilani, K K Birla Goa Campus, India.

We do AI for Science: building machine intelligence that works alongside human
reasoning to accelerate scientific discovery. Our conviction is that AI systems
must go beyond pattern recognition; they need to reason, explain, and collaborate
with humans in the pursuit of scientific knowledge.

## Research themes

Neurosymbolic AI: integrating deep neural networks with symbolic methods such as
Inductive Logic Programming to build models that are accurate, interpretable, and
data-efficient.

Deep learning: sequence models, transformers, LLMs, uncertainty quantification,
and explainability, with a focus on reliability for scientific applications.

Computational biology and drug discovery: AI for gene regulation, genomic
foundation models, multi-omics cancer analysis, and early-stage drug design.

Causality: causal machine learning methods that go beyond correlation to discover
causal structure in biological and clinical data.

[Read more about our research](/research/)

## News

<ul>
{% for item in site.data.news %}
  <li><strong>{{ item.date }}:</strong> {{ item.text }}{% if item.link %} <a href="{{ item.link }}">{{ item.link_text }}</a>{% endif %}</li>
{% endfor %}
</ul>
