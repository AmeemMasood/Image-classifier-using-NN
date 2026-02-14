# Image Classifier using Neural Networks #
A deep learning image classification project built with PyTorch/TensorFlow that classifies images from the CIFAR-10 dataset using a fully connected neural network architecture.


#🎯 Overview#
This project implements an image classification system using a fully connected neural network to classify images from the CIFAR-10 dataset. The model learns to recognize and categorize images into 10 different classes. 


# 📊 Dataset #
CIFAR-10 (Canadian Institute For Advanced Research)

Total Images: 60,000 color images
Image Size: 32x32 pixels
Classes: 10 categories

Airplane,
Automobile
Bird,
Cat,
Deer,
Dog,
Frog,
Horse,
Ship,
Truck

Training Set: 50,000 images
Test Set: 10,000 images



# 🏗️ Model Architecture #
The neural network consists of the following components:
Layers

5 Fully Connected (Linear) Layers

Input layer: 3072 neurons (32×32×3 flattened image)
Hidden layers: [Customizable based on your architecture]
Output layer: 10 neurons (one for each class)



# Activation Function #
ReLU (Rectified Linear Unit): Applied after each linear layer except the output layer
Helps with non-linearity and faster training
Prevents vanishing gradient problem


# Loss Function #
Cross-Entropy Loss: Measures the difference between predicted and actual class distributions
Ideal for multi-class classification problems
Combines LogSoftmax and Negative Log-Likelihood Loss



# Optimizer #
AdamW (Adam with Weight Decay)
Adaptive learning rate optimization
Includes weight decay for better regularization
Learning rate: [0.001]


