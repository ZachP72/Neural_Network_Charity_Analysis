# Neural_Network_Charity_Analysis
Optimizing data for a neural network model 

## Overview
Using my knowledge from machine learning and neural networks for this project I use the features in this dataset I create a binary classifier that will tell the customer whether or not the applicants will be successful using alphabet soup. The dataset contains over 34,000 organizations that have been funded by alphabet soup. There are a number of columns that capture the metadata of each organization such as organization type, the use of funding amongst others. This project is comprised of 3 steps: Preprocessing the data for the neural network, Compile,train and evaluate the model & finally optimizing the model.

## Results

## Data Preprocessing
variable(s) that are considered the target(s) for your model?

- The variable we are targeting in this module is the IS_SUCCESSFUL column.

variable(s) that are considered to be the features for your model

- The features that we are using are every column except the ones that we will drop.

What variable(s) are neither targets nor features were removed

- First features we drop are the 'EIN' & 'NAME' because we expect both features to have little to do with our outcome.

## Compiling, Training, and Evaluating

How many neurons, layers, and activation functions did you select for your neural network model
- This model is made with an input features & two hidden layers. The first hidden layer has 8 neurons, the second has 5 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".
![image](https://user-images.githubusercontent.com/95777297/181657190-6ea65733-085f-454d-a158-bbf30019b090.png)


Was the model able to achieve the target model performance?

- Although we the target for the model was to be 75% or above, I was not able to reach the target.

What steps were taken to try and increase model performance?

- Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.

