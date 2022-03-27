# Neural_Network_Charity_Analysis


## Overview

This analysis used tensorflow to conduct a neural network analysis to predict where to make investments using a charity dataset of 34,000 organizations that have received funding. The data was preprocessed and loaded into a neural network model, trained, and evaluated. The results of this analysis are below.


##Results

Data Preprocessing
The target of this neural network model is whether or not the investment was successful and the money invested in the charity was used effectively.
The features for this model were the application type and classification.
The identification columns, EIN and Name, were not useful to this model and were removed.


## Compilind, Training, and Evaluting the Model

The initial model contained 2 layers with 80 neurons in the first, 30 neurons in the second, and both used the relu activation function. This choice was made to test out a standard model and identify areas for improvement.
The initial model did not receive the target model performance of 75, but received 72% accuracy.
To increase model performance, I tried increasing the number of hidden layers and number of neurons, changing the activation types, and increasing the number of epochs. All methods yielded an accuracy score around 72%.


Summary

The deep learning model was not optimized for optimal target performance to identify which charities to invest in. An SVM may have been a better model to solve this classification problem because it is intended to be a binary classifier and can conduct the same analysis without going very deep.


