---
title:  "Publications"
layout: single
classes: wide
author_profile: true
header:
    overlay_image: /assets/images/header_image_astro.jpg
    overlay_filter: 0.0
---

For a complete list of publications take a look at my [Google Scholar profile](https://scholar.google.fr/citations?user=UJBh1DUAAAAJ&hl=en). A few selected publications, and their corresponding open source code can be found below:

## DL4DS - Deep Learning for empirical DownScaling

* [ArXiv](https://arxiv.org/abs/2205.08967)
* [GitHub](https://github.com/carlos-gg/dl4ds)

We presetn `DL4DS` (Deep Learning for empirical DownScaling), a Python package that implements state-of-the-art and novel deep learning algorithms for empirical downscaling of gridded Earth science data. With `DL4DS`, a low-resolution gridded dataset can be downscaled with the help of an arbitrary number of auxiliary predictor and static variables, and a high-resolution reference dataset. The mapping between the low- and high-resolution data is learned with either a supervised (aka CNN) or a conditional generative adversarial (aka cGAN) Deep Learning model. The training can be done from explicit pairs of high- and low-resolution samples (MOS-style, e.g., high-res observations and low-res numerical weather prediction model output) or only with a HR dataset (PerfectProg-style, e.g., high-res observations or high-res model output). In `DL4DS`, we implement a channel attention mechanism to exploit inter-channel relationship of features by providing a weight for each channel in order to enhance those that contribute the most to the optimizaiton and learning process. Aditionally, a Localized Convolutional Block (LCB) is located in the output module of the networks in `DL4DS`. With the LCB we learn location-specific information via a locally connected layer with biases. `DL4DS` is built on top of Tensorflow/Keras and supports distributed GPU training (data parallelism) thanks to Horovod. 

![DL4DS workflow](https://github.com/carlos-gg/dl4ds/raw/master/docs/img/fig_workflow.png){:width="700px"}

## Supervised detection of exoplanets in high-contrast imaging sequences

* [ArXiv](https://arxiv.org/abs/1712.02841)
* [Astronomy & Astrophysics, 2018](https://www.aanda.org/articles/aa/abs/2018/05/aa31961-17/aa31961-17.html)
* [GitHub](https://github.com/carlos-gg/supervised-detection-exoplanets-hci)

We reformulate the exoplanet detection task (for [angular differential imaging](https://vimeo.com/125547220) sequences) building on well-established machine learning techniques to take high-contrast imaging post-processing from an unsupervised to a supervised learning context. In this new framework, we presented algorithmic solutions using two different discriminative models: SODIRF (random forests) and SODINN (neural networks). The proposed supervised detection framework outperforms state-of-the-art techniques in the task of discriminating planet signal from speckles. For instance, SODINN improves the true positive rate by a factor ranging from ∼2 to ∼10 wrt. low-rank based approaches, working at the same false positive rate. The code has been publicly released and can be found on GitHub.

![SODINN framework](/assets/images/sodinn.png){:width="700px"}

## VIP: Vortex Image Processing Package for High-contrast Direct Imaging

* [ArXiv](https://arxiv.org/abs/1705.06184)
* [Astronomical Journal, 2017](http://iopscience.iop.org/article/10.3847/1538-3881/aa73d7/meta)
* [GitHub](https://github.com/vortex-exoplanet/VIP)

The Vortex Image Processing (VIP) library is a python package dedicated to astronomical high-contrast imaging. It relies on the extensive python stack of scientific libraries and aims to provide a flexible framework for high-contrast data and image processing.

## Low-rank plus sparse decomposition for exoplanet detection in direct-imaging ADI sequences. The LLSG algorithm

* [ArXiv](https://arxiv.org/abs/1602.08381)
* [Astronomy & Astrophysics, 2016](https://www.aanda.org/articles/aa/full_html/2016/05/aa27387-15/aa27387-15.html)
* [GitHub](https://github.com/vortex-exoplanet/VIP/tree/master/vip_hci/llsg)

Inspired by recent advances in machine learning algorithms such as robust PCA, we proposed the Low-rank plus Sparse plus Gaussian noise (LLSG) decomposition of [angular differential imaging](https://vimeo.com/125547220) sequences.

--- 

## PhD Thesis:
*Advanced data processing for high-contrast imaging-Pushing exoplanet direct detection limits with machine learning*, 2017, Université de Liège. Supervisors: Prof. Jean Surdej, Prof. Marc Van Droogenbroeck and Dr. Olivier Absil. [ORBi link](http://orbi.ulg.ac.be/handle/2268/214337).

![Thesis](/assets/images/thesis.jpg){:width="700px"}
