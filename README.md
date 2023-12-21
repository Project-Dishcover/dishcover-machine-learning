# Dishcover-machine-learning
This repository contains a Notebook (`ModelBahan.ipynb`) that demonstrates the process of building a deep learning model for image classification using TensorFlow and Keras with the InceptionV3 method to complete image analysis and object detection for each class, to optimize the training using the EarlyStopping Callback, producing an output image of 150x150 32 batches of 15 classes.

## Overview

The notebook covers the following topics:

1. Importing necessary libraries for the project.
2. Mounting Google Drive to access the dataset files.
3. Defining the paths for the training, validation, and test data directories.
4. Exploring the contents of the training data directory.
5. Image data augmentation using the `ImageDataGenerator` class from Keras.
6. Loading and preprocessing images using the `ImageDataGenerator`.
7. Creating data generators for training, validation, and testing datasets.
8. Visualizing sample images and their corresponding labels.
9. Building a transfer learning model using pre-trained models.
10. Compiling and training the model.
11. Evaluating the model's performance on the test dataset.

## Requirements

To run the notebook, you need the following dependencies:

- [Python 3.x](https://www.python.org/downloads/)
- [Tensorflow](https://www.tensorflow.org/)
- [Keras](https://www.tensorflow.org/guide/keras?hl=id)
- [Tensorflow EarlyStopping](https://www.tensorflow.org/api_docs/python/tf/keras/callbacks/EarlyStopping)
- [InceptionV3](https://keras.io/api/applications/inceptionv3/)
- [numpy](https://numpy.org/)
- [PIL](https://pillow.readthedocs.io/en/stable/)
  
