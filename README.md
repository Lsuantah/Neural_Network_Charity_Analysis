# Neural Network Charity Analysis

## Overview of the analysis

The objective of the analysis is to run big not for profit dataset using neural network to create a binary classifier that can predict a potential donor recipient who will be successful if funded by the charitable organization, Alphabet Soup. 


# Results
## Data Preprocessing
* What variable(s) are considered the target(s) for your model?

The column IS_SUCCESSFUL has binary data which can explain whether the charity donations was used effectively and is considered the target for our deep learning neural network.

* What variable(s) are considered to be the features for your model?

These features of the model are the following columns:
 APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT 

* What variable(s) are neither targets nor features, and should be removed from the input data?

EIN and NAME are identification information and will be removed from the input data.

## Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

layer1 = 80 with activation="relu", layer2 = 30 with activation="relu", Outer layer activation = "sigmoid"

* Were you able to achieve the target model performance?

No, the target model performance was not achieved because there was a Loss: 0.5356, Accuracy: 0.7411

* What steps did you take to try and increase model performance?

Additional hidden layer was inputted and increased the number of neurons in one of the hidden layers, resulting in increased in accuracy to 80.87%


## Summary

* Optimization improved the model significantly to exceed the target of 75% accuracy.



* The classification problem can be resolved using Random Forest Classifier because of the binary classification situation.




