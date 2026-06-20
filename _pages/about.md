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

We are a research group at BITS Pilani, Goa Campus working on **AI for Science**. Our research focuses on bridging the gap between human expertise and machine learning (ML). Rather than relying solely on data-driven learning, we integrate scientific domain knowledge directly into ML models, including deep neural networks. This improves both predictive performance and explainability, enabling AI systems that are not only accurate but also understandable, trustworthy, and useful to scientists.

Our primary focus areas are these:

 - **Neurosymbolic AI**: integrating deep neural networks with symbolic machine learning techniques such as
Inductive Logic Programming to build models that are accurate, interpretable, and data-efficient; 
neurosymbolic inclusion of domain-knowledge into deep networks.

 - **Deep learning**: graph neural networks, sparse neural networks, sequence models, transformers, 
 LLMs, uncertainty quantification, and explainability, with a focus on reliability for scientific applications. 

 - **AI for Science**: AI for gene regulation, genomic foundation models, 
 multi-omics cancer analysis, biomarker discovery, and early-stage drug discovery.

 - **Causal ML**: exploring causal machine learning methods that go beyond correlation to discover
causal structure in biological and clinical data.

Read more about [our research here](/research/).

## News

<ul>
{% for item in site.data.news %}
  <li>{{ item.date }}: {{ item.text | markdownify | remove: '<p>' | remove: '</p>' }}{% if item.link %} <a href="{{ item.link }}">{{ item.link_text }}</a>{% endif %}</li>
{% endfor %}
</ul>

