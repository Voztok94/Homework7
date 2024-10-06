# Homework7
CNN Model Performance Comparison
This repository contains the implementation and comparison of three convolutional neural network (CNN) models trained on different datasets and configurations. We evaluate the models based on prediction accuracy and training speed. The models are:

Original CNN Model (MNIST dataset)
Modified CNN Model (Fashion-MNIST dataset)
Altered CNN Model (Fashion-MNIST dataset with 4096-neuron Dense Layer)

Original Model: The baseline CNN model performs well on the MNIST dataset with fast training and inference times.
Fashion-MNIST Model: The same architecture applied to Fashion-MNIST results in slightly lower accuracy due to the increased complexity of the images, but training and inference times remain similar.
Altered Model with 4096 Neurons: Adding a 4096-neuron dense layer increases the model's capacity and can improve accuracy for complex data, but it comes with significant trade-offs in training time and inference speed. This version may risk overfitting depending on the dataset size and complexity.

Model        |	Dataset        |	Accuracy(%) |	Training Time(sec/epoch) | Inference Time (sec)
Original CNN |  MNIST	         | X%	          | X sec	                   | Y sec
Modified CNN | (Fashion-MNIST) | X%           |	X sec	                   | Y sec
4096 Layer	 | Fashion-MNIST	 | X%	          | X sec	                   | Y sec
