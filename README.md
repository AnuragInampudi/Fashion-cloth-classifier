# Fashion-cloth-classifier


https://colab.research.google.com/drive/1aFHu80XRQ9IdbbALX9Z5X92xMO4uANbH

Authors: Anshu Aditya, Anurag Inampudi

The repository features a Python code for constructing, training, and testing a
neural network with Fashion MNIST to distinguish between the different types of
fashion clothes.
Along with this explanation of the process, visual aids clarify these further.

Table of Contents
• Introduction
• Getting Started
• Data Preprocessing
• Building the Neural Network
• Model Compilation
• Model Training
• Model Evaluation
• Making Predictions
• Visualizing Results

Introduction:
The script below is a python script that utilizes the keras deep learning framework
to classify fashions wear into ten different catagories using the fashion mnist
dataset. It illustrates some important stages of the machine learning process, such
as data pre-processing, forming a model, training, testing and prediction, among
others.

Getting Started:
To use this code, make sure you have the required libraries installed:
numpy for numerical operations.
Building Intelligence with Keras,
Part II: Neural Networks.
Matplotlib: Introduction and Examples.
You can install these libraries using pip:
pip install numpy keras matplotlib

Data Preprocessing:
The code Loads the Fashion MNIST dataset, consisting of gray-scale images of
clothing objects. This converts pixel values into the range of 0-1. This involves pre-
process data so as to enable the neural network learn effectively.

Building the Neural Network:
Creating a Sequential API Keras Neural Network Model.
It consists of three layers:

Reshape layers to flatten the input images.

Dense_layer = [200, ‘ReLU’] or a fully connected layer.

The next layer is entirely a dense layer with 10 units and then softmax as an
activation feature for classification.

Model Compilation:
The model is compiled with essential configuration:
Optimizer: Gradient-based Optimization Using ADAM Optimizer.
Loss function: Multi-Class Classification – Sparse Categorical Cross-Entropy.
Metrics: Accuracy to measure model performance.

Model Training:
The training data along with labels are input into the model for 20 epochs. In turn,
training involves repeatedly adjusting the weights of models to reduce losses.

Model Evaluation:
Testing is done on a set of testing data and its labels after training. Here we check if
the model can be generalized when working with fresh and unseen data.

Making Predictions:
The code shows how to make predictions using the test data and print the predicted
class probabilities. It then derives the predicted class label for each prediction.

Visualizing Results:
The script shows the real versus predicted labels for the first ten test examples and
serves as an initial quantitative evaluation of the model.
Through this code one gets an idea of building a simple image classifier as well as
understanding its result when it comes to Fashion clothing recognition.
Take a look, modify it, and you’ll find out some more about deep learning and image
classification operations.

