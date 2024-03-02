# Neural Networks for Handwritten Digit Recognition (Binary)

This repository contains code for a simple neural network implemented using both Tensorflow/Keras and NumPy. The neural network is designed to recognize handwritten digits of zero and one (binary classification).

- The code implements a neural network for recognizing handwritten digits "zero" and "one."
- Two approaches are used: Tensorflow with Keras and a custom implementation in NumPy.
- The dataset comprises 1000 examples of **20x20 grayscale images** of "zero" and "one."
- Pixel values in the images are represented as floating-point numbers.
- The neural network has three layers with **sigmoid activation functions**.
- The model architecture is defined using the *Keras Sequential model* in Tensorflow.

  
- The code builds and summarizes the model using Tensorflow.
- **Forward propagation** is manually implemented using NumPy for the custom neural network.
- An optional vectorized NumPy implementation for more efficient calculations is provided.
- Pre-trained weights and biases from the Tensorflow model are loaded into the custom NumPy model.
- Predictions are compared between the Tensorflow and NumPy models for a random subset of the dataset.
- Results are visualized to demonstrate the **network's performance** in recognizing handwritten digits.
  
## Usage
To run the code, execute the cells in a Jupyter Notebook environment. Follow the instructions provided in each section, completing exercises if necessary.

## Credits
This code is part of a practice lab for implementing neural networks and is created for educational purposes. It uses concepts from deep learning and machine learning.

Feel free to explore and modify the code for your learning and experimentation.
