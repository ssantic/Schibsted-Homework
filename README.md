SCHIBSTED NLP DATA SCIENCE CHALLENGE
====================================

This file aims to describe the requirements for obtaining the same results that were obtained
by Srdjan Santic when working on the NLP task for Schibsted.

This .zip file contains several files:

* SchibstedNLP-Srdjan_Santic.ipynb
* requirements.txt
* README.md

As a pre-requisite, the interested user first needs to download the Reuters data, as well as
pre-process it. This can be done easily in two steps - all one needs is git and Python 3.

First, the following git repository should be cloned:

$ git clone https://www.github.com/ssantic/reuters-preprocessing

This will obtain the Python files needed for preprocessing, as well as the .sgm datafiles
(in the "data" subfolder). The preprocessing and feature engineering is automatically
done by running:

$ python preprocessing.py


ScibstedNLP-Srdjan_Santic.ipynb
===============================

This is the Jupytor notebook where the entire analysis and modeling is performed. The cells are
meant to be run in order. Please also note that the above two steps can be performed from the
notebook as well.


requirements.txt
================

This file lists all the dependencies needed to run the preprocessing, as well as the Jupyter
notebook. They can be installed by running:

$ pip install -r requirements.txt
