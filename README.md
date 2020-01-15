# FSA

This is a Github repository contains code and instructions for calculating personalized Functional Striatal Abnormalities (FSA) score for individuals with schizophrenia. Details of the method are described in the article:

## Getting Started

- FSA is currently developed based on Python 2.X, requiring Python packages **scipy**, **nilearn**, **sklearn**, **joblib**. 

- Please download the essential materials (e.g. the mask of striatum) from [figshare](https://figshare.com/articles/FSA_score/7150628).

- The FSA is currently developed and validated using the resting-state MRI data preprocessed by [BRANT](http://brant.brainnetome.org/en/latest/index.html). Briefly, the raw fMRI image was preprocessed by slice timing, realign, coregister, normalization and denoising. Our model was validated based on the fMRI version after global signal regression (named 'fdGSRwra*' + origin.nii) and fALFF version after normalization (named 'fALFF_z_' + origin.nii). 

When using BRANT, please cite: 

BRANT: A Versatile and Extendable Resting-State fMRI Toolkit: https://www.frontiersin.org/articles/10.3389/fninf.2018.00052/full, 2018.

- Once established prerequisites above, personalized FSA score can be easily calculated parallelly following instructions and code in **fsa.ipynb**. 

