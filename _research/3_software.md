---
title:  "Scientific software development"
layout: single
classes: wide
permalink: /software/
author_profile: true
excerpt: "Most of the academic code I develop is open and lives on https://github.com/carlos-gg/..."
header:
        overlay_image: /assets/images/header_image_github.jpg
        overlay_filter: 0.0
---

Most of the academic code I develop is [open](https://en.wikipedia.org/wiki/Open_source) and lives on [Github](https://github.com/carlos-gg/).

Below, are highlighted some repositories with code for ongoing and past projects: 

## DL4DS

`DL4DS` (Deep Learning for empirical DownScaling) is a software in the form of a python package, that implements state-of-the-art and novel deep learning methods for super-resolution or downscaling of climate and Earth observation data. DL4DS has been designed with the goal of providing a general framework for training convolutional neural networks with configurable architectures and training procedures to facilitate comparative and ablation studies in a robust way. The methods implemented in DL4DS can be trained in a distributed way on several GPUs. The methods of `DL4DS` handle multiple predictor and auxiliary variables, can operate in perfect prognosis or model output statistics frameworks, can model spatial or spatio-temporal samples, and can be trained in a purely supervised or in an adversarial conditional way. `DL4DS` implements several upsampling techniques and a channel-attention mechanism. A localized convolutional block can be included in the networks of `DL4DS` for learning location (grid point) specific information. [DL4DS repo](https://github.com/carlos-gg/dl4ds).

![DL4DS](https://github.com/carlos-gg/dl4ds/raw/master/docs/img/fig_workflow.png){:width="800px"}

_The general architecture of `DL4DS`. A low-resolution gridded dataset can be downscaled, with the help of (an arbitrary number of) auxiliary predictor and static variables, and a high-resolution reference dataset. The mapping between the low- and high-resolution data is learned with either a supervised or a conditional generative adversarial DL model. The training can be done from explicit pairs of HR and LR samples (MOS-style, e.g., HR observations and LR numerical weather prediction model output) or only with a HR dataset (PerfectProg-style, e.g., HR observations or HR model output)._


## Ecubevis

`Ecubevis` - Earth CUBE VISualization with Python. Intended for the interactive exploration of n-dimensional (2D, 3D, 4D or 5D) arrays on Jupyterlab/Jupyter notebooks. [Ecubevis repo](https://github.com/carlos-gg/ecubevis).

```bash
pip install ecubevis
```
![ecubevis](https://github.com/carlos-gg/ecubevis/raw/master/screenshots/ecubevis_1.png
){:width="800px"}

## SODINN

The `SODINN` package is the consolidation and evolution of the framework proposed in Gomez Gonzalez et al. 2018. This is work in progress and is being developed "in the open" (see the repository on [Github](https://github.com/carlos-gg/sodinn)), as an exercise of open science. This framework for exoplanet detection in multidimensional (3d and 4d arrays) high-contrast imaging datacubes consists of 2 main components: a labeled data generation system and a discriminator, in the form of a deep neural network.  

## VIP

`VIP` is a Python package/library for angular, reference star and spectral differential imaging for exoplanet/disk detection through high-contrast imaging. Check the Github repository [here](https://github.com/vortex-exoplanet/VIP) and the documentation at [readthedocs](http://vip.readthedocs.io/). VIP is available on PyPi:

```bash
pip install vip_hci
```

![VIP](/assets/images/vip.png){:width="800px"}

## HCIplot

High-contrast Imaging Plotting library. The goal of this library is to be the "Swiss army" solution for plotting and visualizing multi-dimensional high-contrast imaging datacubes on Jupyter lab. 

```bash
pip install hciplot
```

![hciplot](/assets/images/hciplot.png){:width="800px"}


## supervised-detection-exoplanets-hci

Code for the paper: ["Supervised detection of exoplanets in high-contrast imaging sequences"](https://www.aanda.org/articles/aa/abs/2018/05/aa31961-17/aa31961-17.html), Gomez Gonzalez et al 2018. Developed in Python 2 but compatible with Python 3. This package enables the generation of labeled data (MLAR smaples) for training machine learning classifiers. It also contains a function for building and training the neural network model that succesfully exploits the 3 dimensions of the training samples (hybrid convolutional and recurrent network). Keras/Tensorflow were used for the implementing network. Finally, it also contains the code for generating the ROC curves (figures 7 and 8) comparing the supervised detection framework to standard model PSF subtraction techniques. Code on [GitHub](https://github.com/carlos-gg/supervised-detection-exoplanets-hci).


## PyAstrOFit

Python package dedicated to the planet orbit fitting using Markov chain Monte Carlo (MCMC) methods. [GitHub repository](https://github.com/vortex-exoplanet/PyAstrOFit).