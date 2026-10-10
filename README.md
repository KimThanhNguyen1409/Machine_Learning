<h1 align="center">Machine Learning </h1>

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python"></a> <a href="https://jupyter.org/"><img src="https://img.shields.io/badge/Jupyter-Notebook-orange.svg" alt="Jupyter"></a><a href="#"><img src="https://img.shields.io/badge/Status-On%20going-brightgreen.svg" alt="Status"></a>
</p>

## Introduction

Welcome to my Machine Learning repository. This project serves as a comprehensive workspace where I implement foundational machine learning algorithms from Coursera (you can visit [Coursera](https://www.coursera.org) to learn more).This repository reflects my journey in bridging the gap between raw data processing and intelligent decision-making systems.

## Implemented Models

Currently, the repository includes the following implementations:

### 1. Basic Model

[Basic Model](Basic_model/basic_model.ipynb)

This is a fundamental linear/logistic classification model. It serves as the baseline for binary classification tasks. The model is built using basic gradient descent to optimize the cost function. It is highly efficient and provides a strong mathematical foundation for understanding weight updates and forward propagation.

### 2. Neural Network Model

[Nerual Network Model](Nerural_Network/Neural_Network.ipynb)

A shallow Neural Network architecture designed for more complex, non-linear tabular data classification.

- **Architecture**: 1 hidden layer with customizable node counts.
- **Activation Functions**: Tanh for the hidden layer and Sigmoid for the output layer.
- **Implementation**: Features fully vectorized forward and backward propagation matrices using NumPy.
- **Application**: Successfully tested on tabular datasets achieving high accuracy on both training and testing sets.

### 3. Deep Neural Network Model v1 & v2

[Deep Neural Network Model](Deep_Nerual_Network/Deep_Neural_Network.ipynb)
[Deep Neural Network Model-v2](Deep_Nerual_Network_v2/Deep_Neural_Network_v2.ipynb)

This model features a higher level of complexity due to its deep architecture. The inclusion of multiple hidden layers significantly enhances its prediction accuracy while maintaining computational efficiency.

- **Architecture**: An L-layer neural network with customizable node counts per layer.
- **Activation Functions**: Sigmoid and ReLU (fully supporting both forward and backward propagation).
- **Implementation**: Vectorized linear forward and backward computations.
- **Application**: Evaluated on a dog and cat image dataset, where the model successfully classifies and distinguishes between the two categories.

About v2, this note book brings more significant features to Deep Neural Network including:

- **Initialize parameters**: There are many new initialize methods such as `initialize_parameters_random`, `initialize_parameters_he`, `initialize_velocity`, `initialize_adam`. These new methods can increase the model in many diffirent ways.
- **Implementation**: `forward_propagation_with_dropout` and `backward_propagation_with_dropout` are new way to implement propagation for the model
- **Update Parameters**: In these new model, there are many ways to update hyper parameters to improve model's performace

<h3>Contact Me</h3>
<p>
  <a href="https://github.com/KimThanhNguyen1409">
    <img src="https://img.shields.io/badge/GitHub-KimThanhNguyen-181717?style=flat&logo=github&logoColor=white"/>
  </a>
  
  <a href="https://www.linkedin.com/in/nguyenkimthanh1409/">
    <img src="https://img.shields.io/badge/LinkedIn-Nguyễn%20Kim%20Thành-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  
  <a href="mailto:nkimthanh47@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-nkimthanh47%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white"/>
  </a>
</p>
