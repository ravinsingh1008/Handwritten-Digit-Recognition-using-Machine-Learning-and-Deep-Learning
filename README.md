# Handwritten Digit Recognition using Machine Learning and Deep Learning
MNIST Data 
The aim of this project is to work with the MNIST dataset that contains handwritten digit images to understand its underlying data structure.

Learning outcomes: 
Basic understanding of machine learning techniques and Python: Learn how machine Learning works and use different Python libraries in deploying machine learning projects

Data preprocessing: Knowledge of how to load and preprocess the MNIST dataset along with normalizing the pixel values and reshaping the data 
Dimensionality reduction unsupervised learning algorithm: Understanding of applying dimensionality reduction algorithms like PCA and t-SNE on the MNIST data 

Data visualization: Learning how to create visualizations like scatter plots and t-SNE embeddings to understand the structure of the MNIST data
Model evaluation: How to evaluate the performance of your model using multiple evaluation metrics 

What it takes to execute this project:
Install required Python libraries like NumPy, Scikit-learn, Pandas, Matplotlib, Seaborn, and Plotly for the project 
Collect MNIST data by web scraping and then preprocess the data by normalizing the pixel values and reshaping the images
Implement dimensionality reduction techniques like PCA using the Scikit-learn library 
Build a simple classifier using a logistic regression model or a neural network  and evaluate its performance 

Real world applications: 
MNIST data can be used in developing handwritten character recognition systems required in document processing and bank check processing 
It can be implemented in the signature verification process to ensure security and authentication 
MNIST dataset serves as the starting point for developing image analysis and classification techniques

## MNIST dataset:

MNIST is a collection of handwritten digits from 0-9. 
Image of size 28 X 28

# Requirements

* Python 3.5 +
* Scikit-Learn (latest version)
* Numpy (+ mkl for Windows)
* Matplotlib

# Introduction
MNIST contains 70,000 images of handwritten digits: 60,000 for training and 10,000 for testing. The images are grayscale, 28x28 pixels, and centered to reduce preprocessing and get started quicker. 

Keras is a high-level neural network API focused on user friendliness, fast prototyping, modularity and extensibility. It works with deep learning frameworks like Tensorflow, Theano and CNTK, so we can get right into building and training a neural network without a lot of fuss.

## Description
This is a 5 layers Sequential Convolutional Neural Network for digits recognition trained on MNIST dataset. I chose to build it with keras API (Tensorflow backend) which is very intuitive. 

## Accuracy
It achieved 99.51% of accuracy with this CNN trained on a GPU, which took me about a minute. If you dont have a GPU powered machine it might take a little longer, you can try reducing the epochs (steps) to reduce computation.

It achieved 98.15% of accuracy on test set of this CNN model trained on GPU.
