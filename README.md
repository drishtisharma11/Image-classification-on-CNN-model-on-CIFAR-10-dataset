# Image-classification-on-CNN-model-on-CIFAR-10-dataset using hyperparameter tuning
# Overview
This project demonstrates image classification on the CIFAR-10 dataset using a Convolutional Neural Network (CNN) with hyperparameter tuning. The goal is to classify 32x32 color images into one of 10 classes, including airplanes, cars, birds, cats, dogs, and more. Hyperparameter tuning is done using Keras Tuner to find the best architecture and training configurations.

# Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images divided into 10 classes:

Airplane
Automobile
Bird
Cat
Deer
Dog
Frog
Horse
Ship
Truck
The dataset contains 50,000 training images and 10,000 test images.

# The CNN model includes:

Convolutional Layers for feature extraction.
Max Pooling Layers for downsampling.
Dropout Layer for regularization.
Dense Layer for classification.
Softmax Activation for output probabilities.
Hyperparameters like the number of filters, learning rate, dropout rate, and dense units are tuned using Keras Tuner.

# Hyperparameter Tuning
The model’s hyperparameters, including:

Number of filters in convolution layers.
Dense layer units.
Dropout rate.
Learning rate.
are tuned to optimize performance using Keras Tuner.

# Training and Evaluation
Load CIFAR-10: The dataset is loaded and normalized.
Hyperparameter Search: Keras Tuner searches for the best hyperparameters.
Model Training: The model is trained using the best hyperparameters.
Evaluation: The model is evaluated on the test set, and the final accuracy is reported.
Visualization: Training and validation accuracy are plotted over epochs.
# Conclusion
This project uses a CNN with hyperparameter tuning to classify images from the CIFAR-10 dataset. Hyperparameter tuning improves the model's performance compared to a standard CNN, and future improvements can be made with more advanced architectures and regularization techniques.
