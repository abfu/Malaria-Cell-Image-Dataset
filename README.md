[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/abfu/classifying_cell_images/master)

![Cells](https://imgur.com/R7AhNUe)

# Malaria-Cell-Image-Dataset
  

### Introduction
The data set contains images of of cells, which are either uninfected or infected by malaria. The goal of this project
is to build and train a convolutional neural network (CNN), to classify these cell images into the categories 'infected'
and 'uninfected. In order to do so, these images need to be loaded as numpy arrays, as the CNN takes tensors as input.
The tensors are of the shape (image height, image width and colour channels). To save memory, i chose a low resolution 
of 32x32 pixels. The cell images are in colour, so three colour channels are needed, whereas greyscale images one channel.
Therefore the input of the CNN is a tensor in the shape of (32, 32, 3).
  
The data set can be found on [Kaggle](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria) and was taken
from the official U.S. National Library of Medicine's [website](https://ceb.nlm.nih.gov/repositories/malaria-datasets/).
Using a convolutional neural network from Keras to classify cells by their presence of malaria.
  
My goal for this project was to learn the basic application of Keras and TensorFlow. I used the tutorials on the TensorFlow [website](https://www.tensorflow.org/tutorials) to build a CNN and was interested in the difference in performance on the GPU and CPU.

### Contents
* Resizing of Images
* Building a CNN with Keras
* Evaluate performance on GPU and CPU
