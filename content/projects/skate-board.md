---
title: "Modelling and Simulating the Skateboard using DEVS Simulator"
description: "Java based Digital Twin. Completed as a part of Course project in CSE-561 Modelling, Simulation and Theory of applications"
dateString: Oct 2023 - Dec 2023
draft: false
tags: ["DEVS", "Modeling and Simulation", "Digital Twin"]
showToc: false
weight: 203
cover:
    image: "projects/skate-board/cover.png"
--- 
### 🔗 [Github](https://github.com/vasavamsi/Modelling-and-Simulating-the-Skateboard-using-DEVS-Simulator)

## Summary
This project is completed as a part of assignment for CSE-561 Modelling, Simulation and Theory of applications. This work leverages the state-of-the-art DEVS simulator to develop the model for Skateboard Generator, Skateboard Transducer and Skateboard models. We also couple these models to create the couple model.

## Pre-installations

This project utilizes the DEVS Simulator package and needs the same to be installed in your device for running the project. The Source code along with documentation for DEVS Simulator version 6.1.0 can be found <a href="https://sourceforge.net/projects/devs-suitesim/files/DEVS_Suite_6.1.0/" style="color: orange;">here</a>. Some of the prior neccessities to be installed are either of JRE versions from 1.8, 11.02, 11.10 and 15.02 and Maven. It is also recommended to install 'Eclipse IDE for JAVA developers', you can find the installation details for the same <a href="https://www.eclipse.org/downloads/packages/installer">here</a>.

## Running the simulation

After downloading the Simulator packaged in your local device, navigate to the folder "DEVS-Suite-Mixerd_Win64_6.1.0\Models\Component\BasicProcessor" and place the .java files from this repository here. Follow the steps as below:

Step 1 - Expand the Package Explorer in the left of the IDE and double click on controller pack (as shown in image below). Now, hower over 'Run As' option and select '1 Java Application'.

![](/projects/skate-board/1.png#center)

Step 2 - Select 'Component Models' in the UI.

![](/projects/skate-board/2.png#center)

Step 3 - Now select the Package as 'Component.BasicProcessor' and Model as any of the desired models provided in this pack. Check the boxes for SimView for Visualization of the model and Tracking to track the simulation.

![](/projects/skate-board/3.png#center)

Step 4 - Now provide the desired inputs and hit the 'Step' button to run the simulation for one step and so on. You can set n desired steps using 'Step(n)' button.

![](/projects/skate-board/4.png#center)

Note - The inputs for each model and coupled model can be modified or increased in the code using the function addTestInput.

Implementation of coupled model:

![](/projects/skate-board/5.png#center)