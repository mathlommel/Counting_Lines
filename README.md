# Counting_Lines

In this project, we aim to build a dataset of 28x28 pixel images with randomly drawn straight lines. The number of lines in each image is randomly selected as an integer between 1 and 10.

The main goal of this work is to build and train a neural network that can detect the number of lines in each image.

## Image Generation
The first challenge is data generation. The images used to train the network will be homemade.

To create random lines on a 28x28 matrix, we randomly select a slope and an intercept. Starting from a point within the image, we can then construct lines based on these characteristics. Special attention is paid to ensure that the lines are continuous. As demonstrated in the notebook, we must add intermediate points to complete the line within the image boundaries.

## Building and Training the Network
In this project, we propose three different architectures:

- A simple MLP (Multi-Layer Perceptron)

- A CNN using 3x3 kernels

- An enhanced version combining 5x5 kernels with 1x1 kernels

All strategies, along with the training results, are documented in the notebook and summarized in the PDF file included in the repository (the project slides).

---
This project was developed entirely using TensorFlow.

-------------------
**Mathematics and Big Data**

*Master Modelling for Science and Engineering*

*UAB, 2024-2025*
