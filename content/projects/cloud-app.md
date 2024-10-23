---
title: "AWS Elastic Application for facial recognition"
description: "This project leveraged various AWS functionalities such as S3, SQS and EC2 along with Lambda and Docker."
dateString: Apr 2023
draft: false
tags: ["AWS", "EC2", "SQS", "S3", "Lambda", "Docker"]
showToc: false
weight: 203
cover:
    image: "projects/cloud-app/architecture.png"
--- 
### 🔗 [Github](https://github.com/vasavamsi/AWS-Elastic-Application-for-facial-recognition/tree/main)

## Summary 
In this project, I built an elastic application that can automatically scale out and in on-demand and cost-effectively by using the PaaS cloud. Specifically, I built this application using AWS Lambda and other supporting services from AWS. AWS Lambda is the first and currently the most widely used function-based serverless computing service. This application demonstrates a meaningful cloud service to users, and the technologies and techniques that learned will be useful to develop more complex cloud based applications.

## Description

This complete cloud app is a video analysis application that uses four Lambda functions to implement a multi-stage pipeline to process videos sent by users.

   1. The pipeline starts with a user uploading a video to the input bucket.
   2. Stage 1: The video-splitting function splits the video into frames and chunks them into the group-of-pictures (GoP) using FFmpeg. It stores this group of pictures in an intermediate stage-1 bucket.
   3. Stage 2: The face-recognition function extracts the faces in the pictures using a Single Shot MultiBox Detector (SSD) algorithm and uses only the frames that have faces in them for face recognition. It uses a pre-trained CNN model (ResNet-34) for face recognition and outputs the name of the extracted face. The final output is stored in the output bucket. The architecture of the cloud application is shown below. We will use AWS Lambda to implement the functions and AWS S3 to store the data required for the functions.

The running instructions are clearly explained in the github readme file.
