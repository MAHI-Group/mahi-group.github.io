---
title: "Research"
permalink: /research/
layout: single
author_profile: true
---

We do AI for Science, that is, building machine intelligence that works alongside
human reasoning to accelerate scientific discovery. Our core conviction is that AI
systems must go beyond pattern recognition: they need to reason, explain, and
collaborate with humans in the pursuit of scientific knowledge. To that end, we
develop methods that combine the scalability of modern deep learning with the
interpretability and structure of symbolic reasoning, and apply them to real-world
scientific problems in computational biology and drug discovery. 
We welcome collaborations on complex, real-world problems; 
if you are interested in working together, 
please feel free to [write to the PI](mailto:tirtharaj@goa.bits-pilani.ac.in).

## Neurosymbolic AI

Statistical learning and symbolic reasoning have complementary strengths. Deep neural
networks learn well from large, noisy data but are opaque and data-hungry. 
Symbolic methods such as Inductive Logic Programming (ILP) are interpretable and data-efficient
but do not scale to raw data easily. We build neurosymbolic methods that integrate
both: neural networks guided by symbolic domain knowledge, and symbolic engines that
learn from neural representations.

Key contributions include Compositional Relational Machines (CRMs), knowledge-guided
graph neural networks (BotGNN, VEGNN), symbolic neural generation (SNG), 
and methods for extracting interpretable rules
from trained networks. Applications span drug discovery, genomics, and other scientific
domains where both data and prior knowledge are available.

## Deep Learning

We work on foundational aspects of deep learning relevant to scientific applications:
sequence models and transformers for genomic data, model calibration and uncertainty
quantification, knowledge distillation, and explainability. A recurring theme is
reliability: predictions in science must come with well-calibrated confidence and
interpretable justification.

We also study large language models (LLMs) for scientific tasks, including using LLMs
with logical feedback for molecular design, and building genomic foundation models that
capture regulatory and codon-usage patterns across eukaryotes.

## AI for Science

Biology is a natural domain for AI for Science: the data are vast, the problems are
hard, and mechanistic interpretability is essential. We work on:
 
  - Gene regulation: modeling the relationship between DNA sequence and gene expression.
  - Genomic foundation models: learning general-purpose representations of genomic sequences.
  - Multi-omics analysis: interpretable and knowledge-guided ML for biomarker discovery and 
  disease subtyping across omics data.
  - Drug discovery: neurosymbolic and graph neural network models for 
  molecular property prediction, lead generation, and explainable screening.
  - Biomedicine: analyzing video, imaging, and clinical text to support diagnosis, 
  assessment, and decision-making.

Research in these directions involves collaborating with scientists from different domains.

## Causal Machine Learning

Correlation-based models are brittle: they fail under distribution shift and cannot
answer interventional or counterfactual questions that science demands. 
We are interested in causal machine learning, specifically in methods that go beyond
associational learning to discover and exploit causal structure in data.

This includes learning causal graphs from observational and interventional data,
integrating causal priors with deep learning, and using causal reasoning to improve
robustness and interpretability of models in biological and clinical settings. A
longer-term goal is to build AI systems that can reason about *why* a biological
phenomenon occurs, not just *that* it occurs, which is a prerequisite for trustworthy
AI in science.

Most of our code is publicly available at [here](https://github.com/MAHI-Group) and
[here](https://github.com/tirtharajdash).
