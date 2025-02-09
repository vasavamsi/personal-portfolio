---
title: "Context-Aware Optimal Transport Learning for Retinal Fundus Image Enhancement"
description: "VK Vasa, P Qiu, W Zhu, Y Xiong, O Dumitrascu, Y Wang.     Accepted at WACV 2025 (Round 2)"
dateString: Sept 2024
draft: false
tags: ["Contextual loss", "Optimal Transport", "GANs", "WACV2025",  "Retinal Image Enhancement"]
weight: 102
cover:
    image: "/blog/Context-OT/Context-OT.png"
---

The work will be presented in the poster presentation session at WACV 2025 in Tucson, AZ. I am also honored to receive the Exponential Learning Grant to present this work.

## Abstract

Retinal fundus photography offers a non-invasive way to diagnose and monitor a variety of retinal diseases, but is prone to inherent quality glitches arising from systemic imperfections or operator/patient-related factors. However, high-quality retinal images are crucial for carrying out accurate diagnoses and automated analyses. The fundus image enhancement is typically formulated as a distribution alignment problem, by finding a one-to-one mapping between a low-quality image and its high-quality counterpart. This paper proposes a context-informed optimal transport (OT) learning framework for tackling unpaired fundus image enhancement. In contrast to standard generative image enhancement methods, which struggle with handling contextual information (e.g., over-tampered local structures and unwanted artifacts), the proposed context-aware OT learning paradigm better preserves local structures and minimizes unwanted artifacts. Leveraging deep contextual features, we derive the proposed context-aware OT using the earth mover's distance and show that the proposed context-OT has a solid theoretical guarantee. Experimental results on a large-scale dataset demonstrate the superiority of the proposed method over several state-of-the-art supervised and unsupervised methods in terms of signal-to-noise ratio, structural similarity index, as well as two downstream tasks.

## Poster 

![](/blog/Contextual-OT/WACV-2025-Poster.png#center)
<!-- ![](/projects/idle-time/model-training.png#center) -->

# Collaborators

- Mayo Clinic, Phoenix AZ
- Medical Imaging and Data Science (MINDS) Lab, Washington University in St. Louis

🔗 [Paper Pre-print](https://arxiv.org/abs/2409.07862)
🔗 [Short Presentation](https://drive.google.com/file/d/1MRxBfQUJbE6AhV6eQtf8NJYoh4AcT1TJ/view?usp=sharing)
🔗 [Code](https://github.com/Retinal-Research/Contextual-OT)

