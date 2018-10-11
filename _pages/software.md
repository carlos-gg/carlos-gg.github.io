---
title:  "Software"
layout: single
permalink: /software/
author_profile: true
---

Feel free to visit my [Github](https://github.com/carlgogo/) profile and check my repositories. Below a few selected ones: 

## VIP

VIP is a Python package/library for angular, reference star and spectral differential imaging for exoplanet/disk detection through high-contrast imaging. Check the Github repository [here](https://github.com/vortex-exoplanet/VIP) and the documentation at [readthedocs](http://vip.readthedocs.io/). VIP is available on PyPi:

```bash
pip install vip_hci
```

![SODINN framework](/assets/images/vip.png){:width="700px"}


## supervised-detection-exoplanets-hci

Code for the paper: ["Supervised detection of exoplanets in high-contrast imaging sequences"](https://www.aanda.org/articles/aa/abs/2018/05/aa31961-17/aa31961-17.html), Gomez Gonzalez et al 2018. Developed in Python 2 but compatible with Python 3. This package enables the generation of labeled data (MLAR smaples) for training machine learning classifiers. It also contains a function for building and training the neural network model that succesfully exploits the 3 dimensions of the training samples (hybrid convolutional and recurrent network). Keras/Tensorflow were used for the implementing network. Finally, it also contains the code for generating the ROC curves (figures 7 and 8) comparing the supervised detection framework to standard model PSF subtraction techniques.

## PyAstrOFit

Python package dedicated to the planet orbit fitting using Markov chain Monte Carlo (MCMC) methods.