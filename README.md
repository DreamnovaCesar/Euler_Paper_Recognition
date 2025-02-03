![Python](https://img.shields.io/badge/python-v3.10+-blue.svg)
[![Build Status](https://travis-ci.org/anfederico/clairvoyant.svg?branch=master)](https://travis-ci.org/anfederico/clairvoyant)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<a name="readme-top"></a>

# Repository Overview

This repository contains supplementary information for our paper titled *"Discovering Octo-Bit-Based Formulas for Shape Descriptors, Simplexes, and Tetravoxels Using Selection-Based Regression"*. It aims to complement the paper and demonstrate the validity of our research findings.

## Included Files

### PDFs

- **`Algorithm.pdf`**: This document details an algorithm that iterates over every voxel in a 3D binary image to compute two fundamental shape descriptors: volume (total count of 1-voxels) and enclosing surface (sum of exposed faces of each voxel).  

- **`Heatmap.pdf`**: This analysis reveals a critical issue of multicollinearity among predictor variables, which arises when independent variables are highly correlated. Multicollinearity hinders traditional regression models from accurately estimating the individual effects of each predictor, leading to unstable and unreliable coefficient estimates.  

- **`Structural.pdf`**: This report provides an in-depth analysis of structural descriptors, including object dimensions, Euler characteristics, and the number of cavities and tunnels in 66 3D objects. These descriptors are crucial for understanding the spatial complexity and topology of the objects, which significantly impact the modeling and analysis of 3D structures.  

- **`Tables_omp.pdf`**: This file contains LaTeX-formatted tables presenting formulas derived from the Orthogonal Matching Pursuit (OMP) regression model. It highlights the most significant formulas obtained through this method, which proved to be the most effective in our study.  

- **`Tables_result_66.pdf`**: This document presents multiple tables comparing state-of-the-art methods with our approach for the 66 voxelized objects analyzed in the experiment. The results confirm identical values for shape descriptors, simplexes, and tetravoxels.  

- **`Tables_result_BraTS.pdf`**: This file provides a comprehensive comparative analysis from Experiment 4, which evaluated medical images from the BraTS 2020 dataset. The results consistently demonstrate that our method achieved 100% accuracy in extracting shape descriptors.  

### CSV Files

Several folders contain CSV files with detailed data for each shape descriptor, simplexes, and tetravoxels. These files include:

- The formulas found for each descriptor.
- The size of each formula.
- The quantity of each descriptor.

Each folder corresponds to the regression model used.

## Co-authors

- Dr. Hermilo Sanchez Cruz

### Built With

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)&nbsp;

### Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

### 🤝🏻 &nbsp;Connect with Me

<p align="center">
<a href="https://www.linkedin.com/in/cesar-eduardo-mu%C3%B1oz-chavez-a00674186/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://twitter.com/CesarEd43166481"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"/></a>