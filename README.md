# DiRAC Federation Project:  *ML for Science* (WP 3.1)


# Table of Contents
- [1. Introduction](#1-introduction)
- [2. Organisation of Files](#2-organisation-of-files)
- [3. Directions for setup](#3-directions-for-setup)
  * [3.1 Using Notebooks on Google Colab](#31-using-notebooks-on-google-colab)
    + [3.2 Notes while running](#32-notes-while-running)
  * [4. Authors, Contributors and Acknowledgments](#4-authors--contributors-and-acknowledgments)
    + [4.1 Authors](#41-authors)
    + [4.2 Contributors](#42-contributors)
    + [4.3 Acknowledgments](#43-acknowledgments)


# 1. Introduction 

This is a set of practical [Jupyter](https://jupyter.org/) Notebooks designed for the DiRAC Federation Project, Work Package 3.1, namely, *ML for Science*. The notebooks have been developed and curated by SciML, in strong collaboration with DiRAC, and its partners. These notebooks cover the domains of Material Sciences, Astronomy/Cosmology, Physics, Healthcare and Fusion Research. There are 23 notebooks in this collection, as outlined in the table below. 

 Domain | Number of notebooks  | 
| :------------ |:---------------:|
| Material    | 6       |    
| Astronomy   | 6       |  
| Physics     | 6       |    
| Healthcare  | 2       | 
| Fusion      | 3       |    

# 2. Organisation of Files 

This repository is organised as follows:

```
├── README.md                           <This file>
├── notebooks_without_solutions/        <Contains notebooks without any solutions> 
├── notebooks_with_solutions/           <Contains notebooks with relevant solutions> 
└── slides                              <Contains the slides introducing the notebooks> 
```


# 3. Directions for Setup

The Notebooks herein are written in Python (we recommend Python 3+), and relies on the following packages: 

* ``tensorflow``
* ``numpy``
* ``pandas``
* ``h5py``
* ``tqdm``
* ``matplotlib``
* ``scipy``
* ``sklearn``
* ``seaborn``
* ``pickle``, and
* ``tables``.

They are not very version specific, and should, in general, work across versions. The notebooks can be run given these dependencies are met, for example on a local system, or on other platforms, such as [Google Colab](https://colab.research.google.com/) or IRIS Cloud. Here, we provide the instructions for Google Colab to access these notebooks from the repository, but these can be used across other platforms. 

## 3.1 Using Notebooks on Google Colab

* Go to Google Colab,  [https://colab.research.google.com/notebooks/intro.ipynb](https://colab.research.google.com/notebooks/intro.ipynb)
*	Click File → Open Notebook
*	Click the tab named "Github"
*	In the search box, enter https://github.com/stfc-sciml/dirac-federation-ml
*	Scroll down and choose the appropriate example you want to run. 
*	Authorise yourself with Google.

### 3.2 Notes while running

* Make sure that the appropriate Runtime Type is set (None, CPU or TPU). We recommend running on a GPU. 
    * Runtime → Runtime Type → Hardware Accelerator = GPU
* If you wish to keep a copy with saved changes, there are two options:
   * To download the notebook to your computer: File → Download .ipynb
   * To save a copy in your Google Drive: File → Save a copy in Drive


## 4. Authors, Contributors and Acknowledgments

These notebooks evolved from different domains with a strong collaboration between SciML and DiRAC collaborators. 

### 4.1 Authors

Jaehoon Cha and Jeyan Thiyagalingam, Scientific Machine Learning Research Group (SciML), Rutherford Appleton Laboratory (RAL), Science and Technology Facilities Council (STFC). 

### 4.2 Contributors

* Keith Butler, Scientific Machine Learning Research Group, RAL, STFC.
* Kuangdai Leng, Scientific Machine Learning Research Group, RAL, STFC.
* Sam Jackson, Scientific Machine Learning Research Group, RAL, STFC.
* Susmita Basak, Scientific Machine Learning Research Group, RAL, STFC.
* Jon Holdship, Leiden University. 
* Gopakumar Vignesh, Culham Centre for Fusion Energy (CCFE), UK Atomic Energy Authority (UKAEA).


### 4.3 Acknowledgments 

We would like to thank Dr Clare Jenner and Professor Mark Wilkinson from DiRAC for funding and facilitating this project. We also would like to thank Professor Nikos Konstantinidis and Dr Chris Backhouse from University College London, for very useful suggestions and discussions. 

