# Neural Network Charity Analysis
---

## Overview
The purpose of this analysis is to create a neural netowrk learning model that determines if organizations will be successful if they receive funding from the Alphabet Soup charity. By creating a model that can accurately predict success rates, the charity can be optimized to ensure they are funding the right organizations.

---

## Results

### Data Preprocessing
##### What variables are considered targets for the model?
- The target variable of this model was the "IS_SUCCESSFUL" column, as it determines if the funding turned out to be successful

##### What variables are neither targets nor features, and should be removed from the data?
- The "EIN" and "NAME" columns did not provide relevant data to help the model perform better, so they were dropped and removed

##### What variables are considered features for the model?
- The remaining variables were considered the features for the model. Those columns were; "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_ANT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT"

### Compiling, Training, and Evaluating the Model
##### How many neurons, layers, and activation functions were selected for the neural network model, and why?
- Throughout the 3 attempts of running the model, I experimented with various neurons and layers, while using the ReLu activation function for all the hidden layers and the Sigmoid activation function for the output layers. I first began with 90 and 50 neurons in 2 hidden layers as an increase from the oroginal model that did not achieve 75% accuracy. In the second attempt, I stayed with 2 layers while increasing the number of neurons. On the last attempt I added an additional layer with 10 neurons. 

Attempt 1: 

Attempt 2:

Attempt 3:


##### Was the target model performance achieved?
- Throughout the 3 attempts, the target model performance was not achieved. All attempts yielded an accuracy just below 73%, which is short of the target of 75%.

Attempt 1:

Attempt 2:

Attempt 3:


##### What steps were taken to try to increase model performance?
- After the first attempt on the model, I attempted to increase the performance by adding more neurons. After the unsuccessful second attempt, I added an additional hidden layer, but this also proved to be unsuccessful. If I were to run more attempts at this model, I would decrease the number of neurons and layers, as well as try additional activation functions. 

---

## Summary
