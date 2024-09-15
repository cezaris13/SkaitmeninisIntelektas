# Artificial intelligence course taken in Vilnius university 2023, autumn semester.

# [Lab1](/lab1/)
## Goal
The aim of this assignment is to analyse the model of an artificial neuron and its working principles, and to learn the basics of artificial neurons.
## Objectives:
- Write an implementation of an artificial neuron in the programming language of your choice. The program has to find the values of the bias and weights, using threshold and sigmoid functions, in order to properly classify the data in the table.
- Write a system of inequalities to be solved in order to select the appropriate values for the biases and weights when the activation function is thresholded.
- Check the graphical system of inequalities to see if the solutions obtained from the graph satisfy the system of inequalities.

|Data|Data|Class|
|-|-|-|
|**x1**|**x2**|**t**|
|-0,2|0,5|0|
|0,2|-0,7|0|
|0,8|-0,8|1|
|0,8|1|1|

More info can be found in [this document](/lab1/AI1.pdf).

# [Lab2](/lab2/)

## Goal:
The aim of the task is to train a single neuron (perceptron) to solve a two-class problem, to test the classification accuracy and error of the trained neuron, and to perform the test on two datasets.

## Objectives:
- Download and prepare data for the breast cancer and sciatica datasets.
- Develop a program to implement the neuron training and testing processes.
- Investigate the dependence of the classification accuracy of the neuron on the number of epochs.
- Investigate how the error values depend on the number of epochs.
- Investigate how classification results depend on different learning rates.
- Investigate how the results depend on the activation function (threshold, sigmoid).
- Find the learning rate, number of epochs, activation function, weights that give the most accurate classification results.
- 
More info can be found in [this document](/lab2/AI2.pdf).

# [Lab3](/lab3/)
## Goal:

To train a neural network to correctly classify data using WEKA.

## Objectives:
- To prepare the data by decomposing it into training-testing data and new data not assigned to any class.
- To construct the following task sequences in WEKA:
  - to perform tests to select appropriate parameters for an artificial neural network
  - classification of new data
  - classification and testing
- Test the first sequence of tasks to determine the appropriate artificial neural network parameters.
- Classify the new data with the resulting DNT.
- Perform the last sequence of tasks and determine the DNT weights to be used in the Excel calculations.
- Calculate the neural outputs with the resulting DNT weights in Excel.
- Compare the resulting neuronal output values in WEKA and Excel.

More info can be found in [this document](/lab3/AI3.pdf).
# [Lab4](/lab4/)

## Goal:
The aim of the task is to train a convolutional neural network on KMNIST data and compare the impact of different architectures, number of discard layers, activation function, optimisation algorithm, data normalisation on classification accuracy and error.

## Objectives:
- Prepare data for network training: partition data into training and testing sets, normalise.
- Develop a software code to train the network with KMNIST data and to test the classification of the trained network.
- Conduct research with convolutional neural networks:
  - Compare the classification accuracy results and error of three different architectures.
  - Compare the classification accuracy and error results of the architectures when no discard layer is added, when one discard layer is added, and when two discard layers are added, as well as when the discard layer probabilities are different.
  - Compare the results of the classification accuracy and error of the architecture when the data are normalised.
  - Compare the results of architectural classification accuracy and error when different activation functions are used.
  - Compare the results of architectural classification accuracy and error when using different optimisation algorithms.

More info can be found in [this document](/lab4/AI4.pdf).
# [Lab5](/lab5/)

## Goal:
The goal of this task is to program a training algorithm for a self-organising neural network (map, SOM), train it with iris data, and obtain the result of clustering the training set.

## Objectives:
- Normalize the inputs of the iris data set.
- Find the SOM program code, modify it to fit the iris data, calculate the quantization error.
- Train SOM on iris data with different maps: 5x5, 10x10.
- Obtain the results of clustering and quantization error on Iris data with different map sizes: 5x5, 10x10.
- The clustering results are displayed in a table.

More info can be found in [this document](/lab5/AI5.pdf).
