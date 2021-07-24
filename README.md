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

