# Generating Faces with Generative Adversarial Networks

## Requirements
* [Python 3 64bit](https://www.python.org/downloads/), preferably [pip](https://pip.pypa.io/en/stable/installing/), [Jupyter Notebook](https://jupyter.org/install)
* Libraries: [NumPy](https://numpy.org/install/), [TensorFlow](https://www.tensorflow.org/install), matplotlib, imageio, PIL, glob, os, json, math, IPython.display, joblib, pandas, SciPy

## Programmed models
5 models were implemented.
* `mnist32x32`: for handwritten digits.
* `lfw32x32bw`: for LFW database (grayscale and cropped).
* `lfw64x48bw`: for LFW database (grayscale).
* `lfw64x48color`: for LFW database.
* `ffhq128x128`: for FFHQ database.

## General information about models
Each model has a similar folder and code structure.
* `analysis`: saved models used for latent space analysis.
* `animations`: animations of training progress in `gif` format.
* `datasets`: saved datasets ready for training.
* `features`: manually labeled samples for analysis.
* `grids`: examples generated during the training.
* `images`: generated images of different kinds.
* `models`: saved models of generator.
* `weights`: saved weights of all models.
* `..._train.ipynb`: code for training of a GAN.
* `..._generate.ipynb`: code for generating images.
* `..._analyze.ipynb`: code for analyzing images.
