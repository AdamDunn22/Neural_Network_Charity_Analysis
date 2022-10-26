# Neural_Network_Charity_Analysis

## Purpose
Use machine learning and neural networks functions in python to analysis the datasets to create binary classifiers that can predict whether an applicant will succeed if funded by Alphbet Soup.

## Results
### Data Preprocessing
* What variable(s) are considered the target(s) for your model?
  * Our target variable for the model is the "IS_SUCCESSFUL" column
  ![target_variable](https://user-images.githubusercontent.com/108701073/197907212-e44f758c-dcdf-4986-ba23-0e06af8f5d89.png)
  
* What variable(s) are considered to be the features for your model?
  * The following variables are considered features: EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL
  
* What variable(s) are neither targets nor features, and should be removed from the input data?
  * The variables that we removed from our model were NAME and EIN.
  ![Screenshot 2022-10-25 203655](https://user-images.githubusercontent.com/108701073/197907625-518b7aed-b229-4521-aa58-584b192c40a2.png)

 
### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
  * The model currently had two hidden layers the first layer contained 80 nodes while the second layer had 30 nodes and both had an activation function of "relu" and "sigmoid".
![neural_network_first](https://user-images.githubusercontent.com/108701073/197908182-4c461822-629f-43da-987a-4878377d80b4.png)

* Were you able to achieve the target model performance?
  * No, we were unable to achieve the target accuracy of 75% as the model achieved an accuracy of 73.05%.
![network_results_first](https://user-images.githubusercontent.com/108701073/197908511-c990092c-f315-424e-8d18-cc25bbaa9737.png)


* What steps did you take to try and increase model performance?

## Summary
