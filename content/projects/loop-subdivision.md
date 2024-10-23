---
title: "Implementation of Loop Subdivision Algorithm using Half Edge Data Structure"
description: "Smoothening the Mesh structures leveraging half-edge data structures."
dateString: Sept 2023 - Oct 2023
draft: false
tags: ["Half-edge", "3D Meshes", "Computer Graphics"]
showToc: false
weight: 203
cover:
    image: "projects/loop-subdivision/cover.png"
--- 
### 🔗 [Github](https://github.com/vasavamsi/Implementation-of-Loop-Subdivision-Algorithm-using-Half-Edge-Data-Structure-in-Python.git)

## Overview
This project implements the Loop algorithm for subdivision of the input mesh to smoothen it. The project is completed using the help of <a href="https://github.com/carlosrojas/halfedge_mesh">half-edge data structures</a>.

## Algorithm 

1.  Create the mesh object using the Classes defined in ‘halfedge_mesh.py’ and get the list of faces in the mesh object.
2. Looping through faces, calculate the mid points for each edge and update the original vertices. I used dictionary to store the new and updated vertices obtained from each face.
3. Created the list of new faces, where each face gives four faces from the six vertices. The list here stores the indices of the new face vertices.
4. Create the .obj or .off file as output.


## Instructions to run the code.

The package runs without any errors in python = 2 environment. Change the following variables in the main.py:

1. mesh – Change the path provided in ‘HalfedgeMesh’ function to read the input file in ‘.off’ format.
2. output_file_path – Output path to save the output file in ‘.obj’ or ‘.off’ format.
3. Obj_output – Boolean parameter to decide the format of output (‘True’ for .obj and ‘False’ for .off ) The needed functions are defined in the ‘utils.py’ file. The comments in the functions explain the input and outputs. For the second iteration, I used the .off file output obtained from the first iteration as an input. The results for first and second iteration (in both .obj and .off format) are placed in ‘results’ folder as a part of submission.

![](/projects/loop-subdivision/results.png#center)