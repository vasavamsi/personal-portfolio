---
title: "GradCAM implementation on X-ray classification"
description: "Understanding medical dataset using X-rays."
dateString: Dec 2023
draft: false
tags: ["DEVS", "Modeling and Simulation", "Digital Twin"]
showToc: false
weight: 203
cover:
    image: "projects/x-ray-classification/cover.jpg"
--- 
### 🔗 [Github](https://github.com/vasavamsi/Pytorch-implementation-of-ResNet18-with-Grad-CAM-on-MININJSRT-dataset-for-classification-task)

## Summary

This project is a Python implementation to Train ResNet18 architecture on MINIJSRT dataset for Direction classification and Gender classification tasks. It also includes the pre-trained weights and Grad-CAM implementation (activation Heatmap generation).

## Dataset

Download Direction classification and Gender classfication dataset from MINIJSRT database. follow this <a href="http://imgcom.jsrt.or.jp/minijsrtdb/" style="color: orange;">link</a> to accomplish the same. Split the dataset into train, validation and test sets.

## Grad-CAM implementation

Gradient-weighted Class Activation Mapping (Grad-CAM) is a technique used in deep learning to visualize and understand the regions of an input image that a model focuses on when making predictions. It's particularly useful for convolutional neural networks (CNNs) in tasks like image classification. Grad-CAM generates a heatmap that highlights the important regions contributing to the model's decision.

**Key Features:**

1. Class-specific: Grad-CAM can generate heatmaps for specific classes, helping to interpret what the model learns for each class.
1. Backpropagation: It uses gradients flowing into the final convolutional layer to produce the heatmap.

Direction classification results are shown below:

![](/projects/x-ray-classification/direction_classification.png#center)

Gender classification results are shown below:

![](/projects/x-ray-classification/gender_classification.png#center)