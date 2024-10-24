---
title: "Machine State prediction using the Temporal Fusion Transformers for Semicoductor fabrication"
description: "This project explores the capabilities of Transformers for Time Series Forecasting"
dateString: Aug 2024 - Present
draft: false
tags: ["Time Series Forecasting", "Temporal Fusion Tranformer", "DEVS", "Modelling and Simulation", "Keras"]
showToc: false
weight: 202
cover:
    image: "projects/idle-time/cover.png"
--- 

## Summary 
This project is a part of my ongoing thesis work, where we are trying to mimic the behaviour of multiple machines in the multi-staged assembly line production. Say there are 5 machines across 3 different stages of the production and are interdependent on each other functionalities and feedback received. There is huge neccessity to forecast the state of machines given any arbitrary configuration of input static variables (such as material composition, fabrication type and lot sequence). This would help the production unit to analyze the power consumption, identifying the idle machines and decide on the utilities. Although the traditional agent/component based simulators are in place for the specific factory setups, they are prone to certain limitations. These simulators are highly computing reliant and comsume lot of computational power and time. As these simulators mimic the process step by step as per the production instructions, given a huge lot size, they take up lot of time to provide the stats and sometimes lead to crashing the hosts. We aim to replace these agents with the help of latest advancements in Machine learning base Time-series analytics.

## Description

We leveraged the Temporal Fusion Transformers (TFT) to accomplish the task. We aimed to forecast the idle time profiles given the Lot configurations as static input features. We curated the data (idle/active profiles) by simulating the Model using DEVS simulator for all the Machines in the intial stage of the production. We used the 3:1 ratio to split the generated sequences for Training and Testing purposes. Then we leveraged TFT model to learn these time series profiles and later on testing this on unseen data. The same is illustrated well in the below figure. 

![](/projects/idle-time/model-training.png#center)

We used keras and tensorflow based python implementation to accomplish this. Our performance is quantified using the confusion matrix, and specialized metrics for the binary time series forecasting. In future, we will be aiming to extrapolate this work to forecast the profiles for all the machines in the entire simulation. 

We are in the process of developing the Github repo for this work. Meanwhile, you can refer to the discussed TFT model from this <a href="https://arxiv.org/abs/2408.09307" style="color: orange;">paper</a>.

