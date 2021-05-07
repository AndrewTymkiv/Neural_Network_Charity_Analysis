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
- Throughout the 3 attempts of running the model, I experimented with various neurons and layers, while using the ReLu activation function for all the hidden layers and the Sigmoid activation function for the output layers. I first began with 90 and 50 neurons in 2 hidden layers as an increase from the oroginal model that did not achieve 75% accuracy. In the second attempt, I stayed with 2 layers while increasing the number of neurons. On the last attempt I drastically decreased the number of neurons, but yielded similar results. 

Attempt 1: 

![attempt1](https://github.com/AndrewTymkiv/Neural_Network_Charity_Analysis/blob/main/screenshots/attempt1.PNG)


Attempt 2:

![attempt2](https://github.com/AndrewTymkiv/Neural_Network_Charity_Analysis/blob/main/screenshots/attempt2.PNG)


Attempt 3:

![attempt3](https://github.com/AndrewTymkiv/Neural_Network_Charity_Analysis/blob/main/screenshots/attempt3.PNG)



##### Was the target model performance achieved?
- Throughout the 3 attempts, the target model performance was not achieved. All attempts yielded an accuracy just below 73%, which is short of the target of 75%.

Attempt 1:

![result1](https://github.com/AndrewTymkiv/Neural_Network_Charity_Analysis/blob/main/screenshots/result1.PNG)


Attempt 2:

![result2](https://github.com/AndrewTymkiv/Neural_Network_Charity_Analysis/blob/main/screenshots/result2.PNG)


Attempt 3:

![result3](https://github.com/AndrewTymkiv/Neural_Network_Charity_Analysis/blob/main/screenshots/result3.PNG)



##### What steps were taken to try to increase model performance?
- After the first attempt on the model, I attempted to increase the performance by adding more neurons. After the unsuccessful second attempt, I decreased the number of neurons, but this also proved to be unsuccessful. If I were to run more attempts at this model, I would try different combinations of neurons and layers, as well as try additional activation functions. 

---

## Summary
In summary, all attempts yielded very similar results, and did not achieve the target performance of 75%. There could be a number of potential reasons for this, such as using an incorrect number of neurons and layers, dropping columns that may have been useful to the model and vice versa, or failing to identify the best activation function to use. If I were to perform this analysis again, I would attempt it with a Support Vector Machine model as a binary classifier would be appropriate for the target value which was whether or not the funding was successful. 
