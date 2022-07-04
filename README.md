# Notebooks for Image analysis

A collection of Jupyter notebooks with image analysis procedures for data from fluorescence microscopy.
The data that is used in the notebooks is a mix of experimental fluorescence images and synthetic data. The data are included in the repository.

## Flatfield-correction.ipynb

This notebook shows how to correct for uneven illumination of the imaging field.

## Split_and_align.ipynb

This notebook shows how to split data from a Multisplit device and subsequently align the separated channels.

## Mix-and-unmix.ipynb

This notebook deals with spectral unmixing. It uses synthetic data and arbitrary mixing of the channels to first demonstrate how the signals are mixed and after show how the data can be unmixed when the mixing matrix is known.

## Python environment

The 'image_env.yml' file can be used to setup the right python environment. use:

conda env create -f image_env.yml

To activate the environment:

conda activate image_env

To list the packages that are in the environment:

conda list --name image_env

#### Issues/feedback
In case of feedback or questions you can:
* contact me on twitter: [@joachimgoedhart](https://twitter.com/joachimgoedhart) 
* Open an issue on Github


