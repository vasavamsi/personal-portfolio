---
title: "Mapping Human face age progression using Contextual loss"
description: Master's Thesis Part-2
dateString: July 2021
draft: false
tags: ["Attention U-Net", "Style Tranfer", "Computer Vision"]
weight: 107
cover:
    image: "/blog/faceagepro/cover.png"
---

## Abstract

Age progression is a process of projection of futuristic aging characteristics
onto the subject face image. This kind of task finds applications in cyber-cell
forensics, age-invariant facial recognition, and in entertainment sectors up to
a certain extent. Most of the previous works tried projecting similar kinds
of texture-based artifacts such as artificial wrinkles and dullness of eyes on
the test subjects. Even, the analysis to convince the aging effects, as well
as identity preservation in the generated images, is not studied in a detailed
manner. In this work, we for the first time used the Attention mechanism in
combination with weighted contextual loss to accomplish age progression of
the human face. We used Attention UNet Generator architecture with the
pyramid architecture of discriminator to aid the realness of the generated
images. We have also shown the ablation studies for generators with differ-
ent blocks in encoder and decoder. By using weighted Contextual loss, we
induced the aging artifacts onto the test subject without losing the original
identity. We have shown how perceptually close the results are to the real
images. Performance evaluation of our work is carried out with the help of
external age estimation and identity matching agents for better convincing
and reliable quantitative analysis. Our method is robust to occlusion and
some regular positions of the faces. This work is done under the guidance
and collaboration of the premier R&D organization Center for Development
of Advanced Computing (C-DAC), Hyderabad.

This work is completed as Part-2 of my Master's Thesis at IIT Gandhinagar under the supervision of <a href="https://iitgn.ac.in/faculty/cse/shanmuganathan" style="color: orange;">Dr. Shanmuganathan Raman</a> and <a href="https://www.linkedin.com/in/ganga-prasad-r-b7a75571/" style="color: orange;">Mr. Ganga Prasad Rajuladevi</a>. 

# Collaborators

- Center for Development of Advanced Computing (C-DAC), Hyderabad, India.

🔗 [Thesis Report](https://drive.google.com/file/d/1bUPyeepx_Ps5f81IhVNxLhOlvTAeHQJu/view?usp=drive_link)

🔗 [Code](https://github.com/vasavamsi/Mapping-Human-face-age-progression-using-Contextual-loss)
