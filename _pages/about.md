---
permalink: /
title: "Machine-and-Human Intelligence Lab"
excerpt: "We do AI for Science at BITS Pilani, Goa Campus."
layout: single
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

We are a research group within the BITS Pilani, Goa Campus.
We do AI for Science: building machine intelligence that works alongside human
reasoning to accelerate scientific discovery. 
Our conviction is that AI systems
must go beyond pattern recognition; they need to reason, explain, and collaborate
with humans in the pursuit of scientific knowledge.

Our primary focus areas are these:

 - **Neurosymbolic AI**: integrating deep neural networks with symbolic methods such as
Inductive Logic Programming to build models that are accurate, interpretable, and
data-efficient.

 - **Deep learning**: sequence models, transformers, LLMs, uncertainty quantification,
and explainability, with a focus on reliability for scientific applications. 

 - **AI for Science**: AI for gene regulation, genomic
foundation models, multi-omics cancer analysis, and early-stage drug discovery.

 - **Causal ML**: exploring causal machine learning methods that go beyond correlation to discover
causal structure in biological and clinical data.

[Read more about our research](/research/)

## News

<ul>
{% for item in site.data.news %}
  <li>{{ item.date }}: {{ item.text | markdownify | remove: '<p>' | remove: '</p>' }}{% if item.link %} <a href="{{ item.link }}">{{ item.link_text }}</a>{% endif %}</li>
{% endfor %}
</ul>

