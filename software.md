---
layout: main
title: Daniël M. Pelt's software contributions
permalink: /software/
---

# Software

## MSDNet
Python implementation of the Mixed-Scale Dense Convolutional Neural Network, as published in:

* Pelt, D. M., & Sethian, J. A. (2018). A mixed-scale dense convolutional neural network for image analysis. *Proceedings of the National Academy of Sciences, 115*(2), 254-259.
* Pelt, D. M., Batenburg, K. J., & Sethian, J. A. (2018). Improving tomographic reconstruction from limited data using mixed-scale dense convolutional neural networks. *Journal of Imaging, 4*(11), 128.

* [\[More Information\]](https://github.com/dmpelt/msdnet)


## The ASTRA Toolbox
The ASTRA Toolbox is a MATLAB and Python toolbox of high-performance GPU primitives for 2D and 3D tomography.
My contribution to ASTRA is mostly the addition of a Python interface to the toolbox and the addition of a plugin system for new reconstruction algorithms.

* [\[More Information\]](http://www.astra-toolbox.com)

## TomoPy
TomoPy is an open-sourced Python toolbox to perform tomographic data processing and image reconstruction of tomographic synchrotron data.
My contribution to TomoPy was to add the ability to reconstruct using the ASTRA toolbox within TomoPy.

* [\[More Information\]](https://tomopy.readthedocs.org)

## SIRT-FILTER
Python package to compute filters and use SIRT-FBP for tomographic reconstruction, as published in:

* Pelt, D.M., & De Andrade, V. (2017). Improved tomographic reconstruction of large-scale real-world data by filter optimization. Advanced Structural and Chemical Imaging 2: 17. [\[link\]](http://rdcu.be/niW6)
* Pelt, D. M., & Batenburg, K. J. (2015). Accurately approximating algebraic tomographic reconstruction by filtered backprojection. In Proceedings of The 13th International Meeting on Fully Three-Dimensional Image Reconstruction in Radiology and Nuclear Medicine (pp. 158-161). [\[link\]](http://oai.cwi.nl/oai/asset/23742/23742D.pdf)

* [\[More Information\]](http://dmpelt.gitlab.io/sirtfilter/)

## PyMR-FBP
PyMR-FBP is a Python implementation of the MR-FBP tomographic reconstruction method, published in:

Pelt, D. M., & Batenburg, K. J. (2014). Improving Filtered Backprojection Reconstruction by Data-Dependent Filtering. *Image Processing, IEEE Transactions on, 23*(11), pp. 4750-4762. [\[link\]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6862004&isnumber=6908104)

* [\[More Information\]](http://dmpelt.github.io/pymrfbp/)

## PyNN-FBP
PyNN-FBP is a Python implementation of the NN-FBP tomographic reconstruction method, published in:

Pelt, D., & Batenburg, K. (2013). Fast tomographic reconstruction from limited data using artificial neural networks. *Image Processing, IEEE Transactions on, 22*(12), pp.5238-5251. [\[link\]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6607157&isnumber=6609090)

* [\[More Information\]](http://dmpelt.github.io/pynnfbp/)

## Mondriaan
Mondriaan is a sequential program to partition sparse matrices and input and output vectors for parallel sparse matrix-vector multiplication.
My contribution was adding the medium-grain partitioning method to the program, which is published in:

Pelt, D. M., & Bisseling, R. H. (2014). A medium-grain method for fast 2D bipartitioning of sparse matrices. *Proceedings IEEE International Parallel & Distributed Processing Symposium 2014*, IEEE Press, pp. 529-539. [\[link\]](http://www.staff.science.uu.nl/~bisse101/Articles/mediumgrain14.pdf)

* [\[More Information\]](http://www.staff.science.uu.nl/~bisse101/Mondriaan/mondriaan.html)

## PyASTRAToolbox
The PyASTRAToolbox code has been merged with the main ASTRA toolbox code.
