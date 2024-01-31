# Implementation Of Backpropagation In Python From Scratch

This repository contains a simple implementation of a neural network for regression using backpropagation. The code is written in Python and utilizes the NumPy library for numerical operations.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Normalization](#normalization)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Testing](#testing)
- [Results](#results)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Introduction

This neural network is designed for regression tasks and is trained using a backpropagation algorithm. It consists of an input layer, a hidden layer with a sigmoid activation function, and an output layer also with a sigmoid activation function.

## Dataset

The dataset used in this example is a 10x10 grid where each row corresponds to two input values (i, j) and their product (i * j).

## Normalization

The dataset is normalized by dividing all values by 100.

## Model Architecture

- Input Layer: 2 neurons
- Hidden Layer: 8 neurons with a sigmoid activation function
- Output Layer: 1 neuron with a sigmoid activation function

## Training

The neural network is trained for 10,000 epochs using the mean absolute error as the loss function. The weights and biases are updated using the backpropagation algorithm.

## Testing

The trained model is tested on a separate set of data to evaluate its performance.

## Results

The results include real and predicted values, mean absolute errors, and accuracy.

## Usage

To use this code, you can clone the repository and run the provided Python script. Make sure to install the required dependencies.

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
python neural_network_regression.py
