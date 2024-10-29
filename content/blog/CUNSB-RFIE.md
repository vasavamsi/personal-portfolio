---
title: "CUNSB-RFIE: Context-aware Unpaired Neural Schrödinger Bridge in Retinal Fundus Image Enhancement"
description: "Xuanzhao Dong, Vamsi Krishna Vasa, Wenhui Zhu, Peijie Qiu, Xiwen Chen, Yi Su, Yujian Xiong, Zhangsihao Yang, Yanxi Chen, Yalin Wang. Accepted at WACV2025 (Round 2)"
dateString: Aug 2020
draft: false
tags: ["Diffusion Model", "Schrodinger Bridge", "WACV2025", "Retinal Image Enhancement"]
weight: 106
cover:
    image: "/blog/CUNSB-RFIE/cover.png"
    # caption: "A sample landmark detection on a photo by Ayo Ogunseinde taken from Unsplash"
---

## Abstract

Retinal fundus photography is significant in diagnosing and monitoring retinal diseases. However, systemic imperfections and operator/patient-related factors can hinder the acquisition of high-quality retinal images. Previous efforts in retinal image enhancement primarily relied on GANs, which are limited by the trade-off between training stability and output diversity. In contrast, the Schrödinger Bridge (SB), offers a more stable solution by utilizing Optimal Transport (OT) theory to model a stochastic differential equation (SDE) between two arbitrary distributions. This allows SB to effectively transform low-quality retinal images into their high-quality counterparts. In this work, we leverage the SB framework to propose an image-to-image translation pipeline for retinal image enhancement. Additionally, previous methods often fail to capture fine structural details, such as blood vessels. To address this, we enhance our pipeline by introducing Dynamic Snake Convolution, whose tortuous receptive field can better preserve tubular structures. We name the resulting retinal fundus image enhancement framework the Context-aware Unpaired Neural Schrödinger Bridge (CUNSB-RFIE). To the best of our knowledge, this is the first endeavor to use the SB approach for retinal image enhancement. Experimental results on a large-scale dataset demonstrate the advantage of the proposed method compared to several state-of-the-art supervised and unsupervised methods in terms of image quality and performance on downstream tasks.

# Collaborators

- Mayo Clinic, Phoenix AZ
- School of Computing, Clemson University
- Medical Imaging and Data Science (MINDS) Lab, Washington University in St. Louis

🔗 [Paper Pre-print](https://arxiv.org/abs/2409.10966)

🔗 [Code](https://github.com/Retinal-Research/CUNSB-RFIE/tree/main)
