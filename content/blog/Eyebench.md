---
title: "EyeBench: A Call for More Rigorous Evaluation of Retinal Image Denoising"
description: "W Zhu, X Dong, X Li, Y Xiong, X Chen, P Qiu, VK Vasa, Z Yang, Y Wang. (Pre-print available)"
dateString: Nov 2024
draft: false
tags: ["Benchmark",  "Retinal Image Enhancement", "Image quality assessment", "Medical expert annotations", "Clinic preference alignment"]
weight: 101
cover:
    image: "/blog/Eyebench/cover_new.jpg"
---

## Abstract

With the advancement of generative models,  fundus image denoising has seen significant advancements. However, the evaluation of these models still presents a considerable challenge. A comprehensive evaluation benchmark for fundus image enhancement is indispensable for three reasons: 1) The existing denoising metric (e.g., PSNR, SSIM) is hardly extended with downstream real-world clinical research (e.g., lesion preserving, Vessel morphology consistency). 2) Lack of comprehensive evaluation for both paired and unpaired-based denoising methods, alongside an expert protocols necessary for accurately assessing clinical value.  3) An ideal evaluation system should provide insights to inform future developments of fundus image enhancement. To this end, we proposed a novel comprehensive benchmark, EyeBench, to provide insights that align enhancement models with actual clinical needs, offering a foundation for future work to improve the clinical relevance and applicability. EyeBench has three appealing properties: 1)  multi-dimensions Clinic alignment downstream evaluation: In addition to evaluating the denoising task, we provide several clinically significant downstream tasks for fundus images: vessel segmentation, DR grading, denoising generalization, and lesion segmentation. 2) Medical Expert guiding evaluation design: We introduce a novel dataset that facilitates comprehensive and fair comparisons between paired and unpaired methods and also provides medical expert manual evaluation protocol (e.g., The ratio of lesion structure changed, background-color changed, and extra structures generated). 3) Valuable insights: Our benchmark provides a comprehensive evaluation of existing methods across each downstream dimension, assisting medical experts in making informed choices. Additionally, we offer further analysis of the challenges faced by current methods.

# Collaborators

- Mayo Clinic, Phoenix AZ
- School of Computing, Clemson University
- Medical Imaging and Data Science (MINDS) Lab, Washington University in St. Louis
- Banner Alzheimer’s Institute

<!-- 🔗 [Paper Pre-print and Code] (releasing soon) -->

🔗 [Paper Pre-print](https://arxiv.org/abs/2502.14260)

<!-- 🔗 [Code](https://github.com/Retinal-Research/Contextual-OT) -->