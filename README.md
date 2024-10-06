# Homework7
CNN Model Performance Comparison
This repository contains the implementation and comparison of three convolutional neural network (CNN) models trained on different datasets and configurations. We evaluate the models based on prediction accuracy and training speed. The models are:

Original CNN Model (MNIST dataset)

Modified CNN Model (Fashion-MNIST dataset)

Altered CNN Model (Fashion-MNIST dataset with 4096-neuron Dense Layer)

Original Model: The baseline CNN model performs well on the MNIST dataset with fast training and inference times.
Fashion-MNIST Model: The same architecture applied to Fashion-MNIST results in slightly lower accuracy due to the increased complexity of the images, but training and inference times remain similar.
Altered Model with 4096 Neurons: Adding a 4096-neuron dense layer increases the model's capacity and can improve accuracy for complex data, but it comes with significant trade-offs in training time and inference speed. This version may risk overfitting depending on the dataset size and complexity.

Original Mnist model has an accuracy of 0.9909999966621399 and took 677 seconds to train.

The fashion-mnist model has an accuracy of 0.9018999934196472 and took 640 seconds to train.

The original Mnist model with a layer of 4096 nuerons had an accuracy of 0.9909999966621399 and took 1846 seconds to train.
