---
layout: default
title: Research
permalink: /research/
---

<nav class="site-nav">
  <a href="/">Home</a>
  <a href="/research/">Research</a>
  <a href="/publications/">Publications</a>
  <a href="/teaching/">Teaching</a>
  <a href="/Yifei_Cai_CV.pdf" target="_blank" rel="noopener">CV</a>
</nav>

# Research

My research asks how advanced AI can be both **privacy-preserving and practical**. I work at the intersection of AI security and privacy, machine learning, and secure computation, co-designing model structures, cryptographic operations, and inference systems. My research trajectory connects HE-aware model optimization, efficient secure Transformers, and emerging privacy-preserving LLM systems.

## Privacy-Preserving Machine Learning

My Ph.D. research focused on **cryptography-aware model optimization**: reducing operations that are expensive under homomorphic encryption (HE), rather than relying only on conventional metrics such as parameter count or plaintext computation. I developed HE-friendly structured pruning in [Hunter (AsiaCCS 2022)](https://doi.org/10.1145/3488932.3517401) and the prune-and-assemble approach in [MOSAIC (AsiaCCS 2024)](https://doi.org/10.1145/3634737.3637680). My work on [HE-efficient neural architectures (SaTML 2026)](https://doi.org/10.1109/SaTML68715.2026.00056) further explores how models can be constructed around the computational characteristics of private inference.

The common goal is to make efficiency gains translate into **lower cryptographic execution cost**, not merely smaller models.

## Secure & Efficient AI Systems

Beyond static model optimization, secure Transformer inference requires efficient handling of dynamic computation, costly nonlinear operations, and communication. I developed [SecDTD (EuroS&P 2026)](https://doi.org/10.1109/EuroSP68448.2026.00050), a dynamic token-dropping approach for secure Transformer inference, achieving up to **4.47× end-to-end acceleration**. Its oblivious median-selection protocol, OMSel, achieves up to **16.9× speedup over Bitonic Sort** for secure token selection.

This work motivates a broader model–protocol–system co-design perspective: optimization decisions should account for the actual secure execution pipeline. The [DegreeSpar preprint](https://arxiv.org/abs/2609.32204) further investigates structured degree sparsity for efficient secure Transformer inference.

## Secure & Private Foundation Models

In my current postdoctoral research at Iowa State University, I am investigating **selective privacy protection for LLM inference**. The central idea is to distinguish information that requires protection from computation that can remain in plaintext, and to study how this separation affects privacy requirements, model utility, and practical inference cost.

This is **ongoing research**, rather than a completed or deployed system. My collaborations also extend to broader AI security questions, including coauthored research on data-free backdoor attacks in vision Transformers ([DF-LoGiT, ICML 2026](https://proceedings.mlr.press/v306/shen26a.html)).

## Future Faculty Research Agenda

My long-term goal is to establish an independent program in **AI security and privacy, privacy-preserving machine learning, and secure and efficient AI systems**. I envision three connected directions: developing selective and well-defined privacy protections for foundation-model workflows; co-optimizing model architectures, inference algorithms, and cryptographic protocols; and building reusable research systems that can be evaluated under realistic computing and communication constraints.

These directions extend my prior work from individual inference optimizations toward practical secure AI methods and platforms that can support applications and interdisciplinary collaborations.

## Collaboration & Proposal Development

I have contributed technical sections to an **NSF cybersecurity research proposal** on cryptography-aware model compression and efficient private inference. I am also developing concepts for an interdisciplinary privacy-preserving AI research platform combining automated secure-model conversion, selective data protection, and distributed edge–cloud computing.

For a complete publication record and details of my research experience, see [Publications](/publications/) and my [CV (PDF)](/Yifei_Cai_CV.pdf).
