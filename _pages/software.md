---
title:  "Software"
layout: single
permalink: /software/
author_profile: true
header:
        overlay_image: /assets/images/header_image_github.jpg
        overlay_filter: 0.0
---

Almost everything I code is open source and goes to [Github](https://github.com/carlgogo/). Feel free to take a look. Below, a few selected repositories with code for astronomical high-contrast imaging: 

## SODINN

The SODINN package is the consolidation and evolution of the framework
proposed in Gomez Gonzalez et al. 2018. This is work in progress and is
being developed "in the open" (see the repository on [Github](https://github.com/carlgogo/sodinn)), as an exercise of open science. This framework
for exoplanet detection in multidimensional (3d and 4d arrays) 
high-contrast imaging datacubes consists of 2 main components: a 
labeled data generation system and a discriminator, in the form of a 
deep neural network.  

## VIP

VIP is a Python package/library for angular, reference star and spectral differential imaging for exoplanet/disk detection through high-contrast imaging. Check the Github repository [here](https://github.com/vortex-exoplanet/VIP) and the documentation at [readthedocs](http://vip.readthedocs.io/). VIP is available on PyPi:

```bash
pip install vip_hci
```

![VIP](/assets/images/vip.png){:width="800px"}


## VIP extras

Datacubes, Jupyter tutorials and other materials related to VIP.

## HCIplot

High-contrast Imaging Plotting library. The goal of this library is to be the "Swiss army" solution for plotting and visualizing multi-dimensional high-contrast imaging datacubes on Jupyter lab. 

```bash
pip install hciplot
```

![hciplot](/assets/images/hciplot.png){:width="800px"}


## supervised-detection-exoplanets-hci

Code for the paper: ["Supervised detection of exoplanets in high-contrast imaging sequences"](https://www.aanda.org/articles/aa/abs/2018/05/aa31961-17/aa31961-17.html), Gomez Gonzalez et al 2018. Developed in Python 2 but compatible with Python 3. This package enables the generation of labeled data (MLAR smaples) for training machine learning classifiers. It also contains a function for building and training the neural network model that succesfully exploits the 3 dimensions of the training samples (hybrid convolutional and recurrent network). Keras/Tensorflow were used for the implementing network. Finally, it also contains the code for generating the ROC curves (figures 7 and 8) comparing the supervised detection framework to standard model PSF subtraction techniques. Code on [GitHub](https://github.com/carlgogo/supervised-detection-exoplanets-hci).

## PyAstrOFit

Python package dedicated to the planet orbit fitting using Markov chain Monte Carlo (MCMC) methods. [GitHub repository](https://github.com/vortex-exoplanet/PyAstrOFit).