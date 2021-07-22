# Neural Network Charity Analysis

## Overview

This project sought to create a neural network to create a binary classifier that is capable of predicting whether applicants to Alphabet Soup's grant program will be successful if funded.

### Purpose

Our friend Beks has been tasked by Alphabet Soup to create a model that can predict the success of applicants to Alphabet Soup's grant program that receive funding. This was accomplished by the creation of neural network that could efficiently sift through the data and classify applicants as 'successful' or 'unsuccessful'.

## Results

### Data Preprocessing
- We consider the 'IS_SUCCESSFUL' column as our target variable, since this is what we hope to determine with our neural network.
- We consider 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', and 'SPECIAL_CONSIDERATIONS' to be features of the model.
- 'ASK_AMT' and 'STATUS' are not considered features or targets, and thus were removed from consideration in the model. Additionally, once the categorical variables were encoded in the dataset, we removed 'SPECIAL_CONSIDERATIONS_N' since it provided the same information as 'SPECIAL_CONSIDERATIONS_Y'.

### Compiling, Training, and Evaluating the Model
- How many neurons, layers and activation functions did you select for your neural network model? Why?
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?

## Summary
Summarize the overall results of the deep learning model

### Recommendations
Recommend for how a different model could solve this classification problem. Explain your recommendation.
