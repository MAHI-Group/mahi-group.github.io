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

We are a research group at BITS Pilani, Goa Campus working on **AI for Science**. Our core focus is on bridging the gap between human expertise and machine learning (ML). Rather than relying solely on data-driven learning, we integrate established scientific domain knowledge directly into ML models, including deep neural networks. This approach enhances both predictive performance and model explainability, enabling systems that are not only accurate but also understandable to humans. Our models do more than simply recognize patterns; they incorporate scientific understanding and communicate their reasoning in ways that scientists can interpret, trust, and act upon.

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

