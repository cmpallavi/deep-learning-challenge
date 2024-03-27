# deep-learning-challenge
# Charity Funding Predictor

## Overview
The goal of this project is to create an algorithm using machine learning and neural networks to predict whether applicants will be successful if funded by the fictional non-profit foundation, Alphabet Soup.

## Results

### Run 1

Data Preprocessing

* What variable(s) are the target(s) for your model? 
    * IS_SUCCESSFUL
* What variable(s) are the features for your model? 
    * All columns apart from IS_SUCCESSFUL
* What variable(s) should be removed from the input data because they are neither targets nor features? 
    * EIN, NAME
#### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why? 
    * 2 layers
    * layer1 = 10, layer2 = 6, activation function = 'relu'. This was random guesses.
* Were you able to achieve the target model performance?
    * No . 73.02% accuracy
* What steps did you take in your attempts to increase model performance?
    * Removed ASK_AMT from the feature set and changed the neurons.

### Run 2
* What variable(s) are the target(s) for your model? 
  * IS_SUCCESSFUL
* What variable(s) are the features for your model? 
  * All columns apart from IS_SUCCESSFUL
* What variable(s) should be removed from the input data because they are neither targets nor features? 
  * EIN, NAME, ASK_AMT
#### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why? 
  * 2 layers
    * layer1 = 80, layer2 = 30, activation function = 'relu'. This was random guesses.
  * Were you able to achieve the target model performance?
    * No. 73/04% accuracy
* What steps did you take in your attempts to increase model performance?
  * Add another layer.

### Run 3 
* What variable(s) are the target(s) for your model? 
    * IS_SUCCESSFUL
* What variable(s) are the features for your model? 
    * All columns apart from IS_SUCCESSFUL
* What variable(s) should be removed from the input data because they are neither targets nor features? 
    * EIN, NAME, ASK_AMT
#### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why? 
    * 3 layers
    * layer1 = 80, layer2 = 30, layer3 = 60 activation function = 'relu'. This was random guesses.
* Were you able to achieve the target model performance?
    * No. 72.8& accuracy
* What steps did you take in your attempts to increase model performance?


## Summary
In the three attempts I made, the model was unable to achieve a target predictive accuracy higher than 73.2%. Tuning, changing Binning limits, adding a layer in modeling resulted in not much improvement. I would consider using another classification model to see if it is better at predicting whether applicants will be successful if funded by Alphabet Soup.


## My Code
* Jupyter Notebook: 
1. Starter_code.ipynb, 
2. starter_code_optimization_1.ipynb, 
3. starter_code_optimization_2.ipynb