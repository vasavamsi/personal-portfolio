---
title: "Spherical Conformal Mapping using Python"
description: "Python implementation of paper Genus Zero Surface Conformal Mapping"
dateString: Oct 2023 - Dec 2023
draft: false
tags: ["3D Meshes", "3D Transformation"]
showToc: false
weight: 206
cover:
    image: "projects/spherical-map/cover.jpg"
--- 
### 🔗 [Github](https://github.com/vasavamsi/Spherical-Conformal-Mapping-using-Python)

## Overview
This work is the python implementation of math work explained in the paper <a href="https://ieeexplore.ieee.org/document/1318721">Genus Zero Surface Conformal Mapping</a>. I completed this work as a part of Course porject in the course "CSE 570 Advanced Computer Graphics I". The project is completed using the help of <a href="https://github.com/carlosrojas/halfedge_mesh">half-edge data structures</a>.

## Algorithm 


   1. Converted the input mesh object ('brain.off' here) into a gauss map.
   2. We then iterate to optimize the tuette energy (algorithm 1) to get the tuette embedding.
   3. Using the tuette embedding, we iterate over to optimize the harmonic energy with the energy difference threshold as 1e-5 (can be adjusted). The converged harmonic energy for 'brain.off' comes out to be approximately 25.
   4. Create the .obj or .off file for the final conformal mapping.


## Instructions to run the code.

The package runs without any errors in python = 2 environment. Change the following variables in the main.py:


1. mesh – Change the path provided in ‘HalfedgeMesh’ function to read the input file in ‘.off’ format.
2. file_path – Output path to save the output file in ‘.obj’ or ‘.off’ format. The helper functions are defined in the ‘utils.py’ file. The comments in the functions explain the input and outputs. The obtained result is placed in the results folder.


![](/projects/spherical-map/results.png#center)

Note: As we have no way to include the texture information, visualization would be hard in the case of python implemantation.