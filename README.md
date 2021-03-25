# Neural_Network_Charity_Analysis

## Overview

Using my knowledge of machine learning and neural networks, I used the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Utalizing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Results
### Data Preprocessing
What variable is considered the target for your model?
  -IS_SUCCESSFUL Column
What variable is considered to be the features for your model?
  -All Columns minus IS_SUCCESSFUL Column
What variable is neither targets nor features, and should be removed from the input data?
  -I dropeed EIN, NAME because they have very little impact on the outcome

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
  -My first layer had 80 neurons and second had 20 layers , third I had 5
 <img width="946" alt="Screen Shot 2021-03-25 at 3 07 37 PM" src="https://user-images.githubusercontent.com/72036895/112543929-08523b00-8d7c-11eb-81f1-35509de7a919.png">

Were you able to achieve the target model performance?
  -No, I was only able to get about 52% accuracy
 <img width="684" alt="Screen Shot 2021-03-25 at 3 07 29 PM" src="https://user-images.githubusercontent.com/72036895/112543980-1738ed80-8d7c-11eb-92c5-6ef80fde4868.png">

What steps did you take to try and increase model performance?
  -I tried to add more layers, more neurons ,activation function and adjusted data cleaning process

## Summary
The model ended up with the accuracy score of 52% after optimization. The Initial neural network had an acuarcy of 49% so this is a 3% increase in accuracy. 
