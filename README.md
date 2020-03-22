# FSA

This is a Github repository contains code and instructions for calculating personalized Functional Striatal Abnormalities (FSA) score for individuals with schizophrenia. Details of the method are described in the article:

A neuroimaging biomarker for striatal dysfunction in schizophrenia. 

## Getting Started

- FSA is currently developed based on Python 2.X, requiring Python packages **scipy**, **nilearn**, **sklearn**, and **joblib**. 

- Please download the essential materials (e.g. SVM model) from [figshare](https://figshare.com/articles/FSA_score/7150628).

- The FSA is currently developed and validated using the resting-state MRI data preprocessed by a open-source tool [BRANT](http://brant.brainnetome.org/en/latest/index.html). Briefly, the raw fMRI image was preprocessed by slice timing, realign, coregister, normalization and denoising. Our model was validated based on the preprocessed fMRI images with global signal regression ('fdGSRwra*') and normalized fALFF images ('fALFF_z_'). 

- Once established prerequisites above, personalized FSA score can be easily calculated parallelly following instructions and code in **fsa.ipynb**. 

When using BRANT, please cite: 

* BRANT: A Versatile and Extendable Resting-State fMRI Toolkit: https://www.frontiersin.org/articles/10.3389/fninf.2018.00052/full, 2018.


## Copyright Information
The materials and code to calculate personalized FSA score is available for noncommercial use and exclusively for research purpose. For potential commercial use, please contact Bing Liu at bliu@nlpr.ia.ac.cn.

