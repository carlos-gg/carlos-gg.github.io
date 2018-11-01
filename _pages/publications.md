---
title:  "Publications"
layout: single
permalink: /publications/
author_profile: true
---

For a complete list of publications take a look at my [CV](https://carlgogo.github.io/assets/cv/cv.pdf) or my [Google Scholar profile](https://scholar.google.fr/citations?user=UJBh1DUAAAAJ&hl=en).

## Selected publications (with the corresponding open source code):

### Supervised detection of exoplanets in high-contrast imaging sequences

* [ArXiv](https://arxiv.org/abs/1712.02841)
* [Astronomy & Astrophysics, 2018](https://www.aanda.org/articles/aa/abs/2018/05/aa31961-17/aa31961-17.html)
* [GitHub](https://github.com/carlgogo/supervised-detection-exoplanets-hci)

> We reformulate the exoplanet detection task (for [angular differential imaging](https://vimeo.com/125547220) sequences) building on well-established machine learning techniques to take high-contrast imaging post-processing from an unsupervised to a supervised learning context. In this new framework, we presented algorithmic solutions using two different discriminative models: SODIRF (random forests) and SODINN (neural networks). The proposed supervised detection framework outperforms state-of-the-art techniques in the task of discriminating planet signal from speckles. For instance, SODINN improves the true positive rate by a factor ranging from ∼2 to ∼10 wrt. low-rank based approaches, working at the same false positive rate. The code has been publicly released and can be found on GitHub.  

![SODINN framework](/assets/images/sodinn.png){:width="700px"}

### VIP: Vortex Image Processing Package for High-contrast Direct Imaging

* [ArXiv](https://arxiv.org/abs/1705.06184)
* [Astronomical Journal, 2017](http://iopscience.iop.org/article/10.3847/1538-3881/aa73d7/meta)
* [GitHub](https://github.com/vortex-exoplanet/VIP)

> The Vortex Image Processing (VIP) library is a python package dedicated to astronomical high-contrast imaging. It relies on the extensive python stack of scientific libraries and aims to provide a flexible framework for high-contrast data and image processing. 

### Low-rank plus sparse decomposition for exoplanet detection in direct-imaging ADI sequences. The LLSG algorithm

* [ArXiv](https://arxiv.org/abs/1602.08381)
* [Astronomy & Astrophysics, 2016](https://www.aanda.org/articles/aa/full_html/2016/05/aa27387-15/aa27387-15.html)
* [GitHub](https://github.com/vortex-exoplanet/VIP/tree/master/vip_hci/llsg)

> Inspired by recent advances in machine learning algorithms such as robust PCA, we proposed the Low-rank plus Sparse plus Gaussian noise (LLSG) decomposition of [angular differential imaging](https://vimeo.com/125547220) sequences. 


## PhD Thesis:
> Advanced data processing for high-contrast imaging-Pushing exoplanet direct detection limits with machine learning_. 2017, Université de Liège. Supervisors: Prof. Jean Surdej, Prof. Marc Van Droogenbroeck and Dr. Olivier Absil. [ORBi link](http://orbi.ulg.ac.be/handle/2268/214337).

![Thesis](/assets/images/thesis.jpg){:width="700px"}


------------


_"Essentially, all models are wrong, but some are useful"_, George Box.

_"...if the model is going to be wrong anyway, why not see if you can get the computer to ‘quickly’ learn a model from the data, rather than have a human laboriously derive a model from a lot of thought"_, Peter Norvig.