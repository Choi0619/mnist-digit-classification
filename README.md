# MNIST Handwritten Digit Classification

This project demonstrates the classification of handwritten digits from the MNIST dataset using a fully connected neural network (MLP). The MNIST dataset is widely used in machine learning for training and evaluating models on image classification tasks. The neural network implemented here predicts the digit (0-9) based on the 28x28 pixel grayscale images provided in the dataset.

### Dataset Overview
The MNIST dataset contains 60,000 training images and 10,000 test images, all of which represent grayscale handwritten digits. Each image is 28x28 pixels, making it a suitable dataset for beginners and neural network testing.
![image](https://github.com/user-attachments/assets/3cf8f159-4d1f-48db-90e8-f627fc3428c4)  

*Figure 1: MNIST Handwritten Digits Examples.*

### Neural Network Architecture
The model implemented in this project is a Multi-Layer Perceptron (MLP) with two hidden layers:
- The first hidden layer consists of 128 units with ReLU activation.
- The second hidden layer also consists of 128 units with ReLU activation.
- The output layer consists of 10 units corresponding to the digits 0-9.
- The model uses the Cross Entropy Loss function, and the optimizer used is Adam.

The following image illustrates the general architecture of the fully connected neural network (MLP) used in this project.
![image](https://github.com/user-attachments/assets/d185586a-1613-49dd-af77-bcdeccc949da)  

*Figure 2: Multi-Layer Perceptron (MLP) Architecture used for MNIST Classification.*

### Training Process
- The network was trained over 100 epochs using the Adam optimizer with a learning rate of 0.001.
- The training accuracy and test accuracy were recorded after each epoch to evaluate the performance.
- The model achieved high accuracy on both training and test datasets.

### Future Enhancements
While this project focuses on a simple MLP, future iterations could incorporate Convolutional Neural Networks (CNNs) and other deep learning techniques like dropout and batch normalization to enhance accuracy and generalization performance.
