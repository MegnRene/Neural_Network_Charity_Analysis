# Neural_Network_Charity_Analysis
## Overview
  With knowledge of machine learning and neural networks I used a CSV dataset, containing more than 34,000 organizations that received funding from Alphabet Soup that has a number of columns that capture metadata about each orgainzation, to create a binary classsifier that is capable of predicting weather applicants will be successful if funded by Alphabet Soup. 

*I established that the target variable is the "IS_SUCCESSFUL" column, then removed the "EIN" and "NAME" columns as they did not offer any relevant data that could help the model perform better. The remaining columns became the features for the model.


Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
* I attempted to add layers, and hidden nodes. I tried relu for the layer activation and sigmoid for the output layer. 
Were you able to achieve the target model performance?
* I was not able to achieve the target model performance. My accuracy stayed at 72%
What steps did you take to try and increase model performance?
*I tried 150, 100, and 50 epoch's, only 2 layers, and dropping "status" as well as "ein", and "name" from the data frame in hopes less unuseful data would help the model perform better. 

## Summary
My attemps were unsuccessful in bringing up the accuracy score. Maybe try the random forest classifier as it is less influenced by outliers to get a better score. 
