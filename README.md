# Neural Network Charity Analysis

## Overview

From Alphabet Soup’s business team, a representative received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

The objective is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

### Deliverables

- Deliverable 1: Preprocessing Data for a Neural Network Model
- Deliverable 2: Compile, Train, and Evaluate the Model
- Deliverable 3: Optimize the Model
- Deliverable 4: A Written Report on the Neural Network Model (README.md)

### Code

- AlphabetSoupCharity.ipynb [code](AlphabetSoupCharity.ipynb)
- AlphabetSoupCharity_Optimization.ipynb [code](AlphabetSoupCharity_Optimization.ipynb)

## Results

### Data Preprocessing
- Target variable(s) for the model:  IS_SUCCESSFUL
- Feature variable(s) for the model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS
- Variable(s) that are neither targets nor features, and should be removed from the input data: EIN, NAME, 

### Compiling, Training, and Evaluating the Model
- Number of neurons: first layer 120, second layer 30, third layer 10
- Number of layers: 3
- Number of activation functions: first layer : relu, second layer: sigmoid, third layer: sigmoid, output layer: sigmoid
- Were you able to achieve the target model performance?  Target model performance achieved 79.5%
- What steps did you take to try and increase model performance?  Increase layers, add NAME back into machine learning algorithm

## Summary

- Summary of overall results of the deep learning model. 

- Model 1 accuracy

![Model1_accuarcy](https://user-images.githubusercontent.com/98564776/172979907-fe9e8139-bc95-494b-8740-8a9b2d8ff1c6.PNG)

- Random Forest Model Accuracy

![Random_Forest_Model_accuracy](https://user-images.githubusercontent.com/98564776/172979969-7eb25857-c6d8-4118-8f69-3b0b08892a7d.PNG)


The Random Forest Model can solve the objective in this scenario. It runs efficiently on large data samples and can rank important variables successfully to optimize performance. 

