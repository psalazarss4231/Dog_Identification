# Dog_Identification
The goal is to classify images of dogs according to their breed.



## Description of the Convolutional Neural Networks (Dog_App) project

In this project, we apply convolutional neural networks (CNN) and transfer learning to build a pipeline that processes user images for the following reasons:
1. CNNs are used to identify images.
2. 2. Transfer learning is reused to reuse a model for other classifications.

Our project identifies and gives a suggestion of the breed of the dog of the image that is supplied by means of a classification algorithm, in case of being an image of a human the algorithm will identify it, and in a third case if it is an object He will say that he is not a dog or a human.

## Contents
1. [Motivation](#m)
2. [File structure](#e)
3. [Instructions](#i)
4. [Acknowledgments](#a)
5. [Content](#c)
6. [Findings](#h)
7. [Author](#auth)

<a name="m"></a>

### Motivation

This is a Nanodegree data scientist project and consists of using neural networks (CNN) for image classification.

<a name="e"></a>

### Structure of files and libraries

Models:

-weights.best.from_scratch.hdf5 # Initial model
-weights.best.VGG16.hdf5561 kBan hour ago
-weights.best.Xception.hdf5

Libraries:

-sklearn.datasets import load_files
-keras.utils import np_utils
-numpy as np
-glob
-IPython.display
-IPython.core.display
-IPython.display


<a name="i"></a>

### Instructions
1. Open the ipynb file to analyze or play with it.
3. Upload new images to classify them.


<a name="h"></a>

### Findings

-
- The starter model achieved a test accuracy of 44%, which is up from the 41% accuracy with the VGG16 model.
- However, the final model has an accuracy of 84%, much higher than 60%.

Improvements that can be applied to the model:

- The model can be improved by giving more training images
- Increasing the nodes.
- Increasing the number of layers.

<a name="authors"></auth>

### Author

- [Pamela Salazar](https://github.com/psalazarss4231)

