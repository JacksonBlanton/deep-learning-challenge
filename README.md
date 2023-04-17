# deep-learning-challenge

## Overview
The purpose of this analysis was to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results
- Data Preprocessing

  - What variable(s) are the target(s) for your model?
    - the target is the is_successful parameter
  - What variable(s) are the features for your model?
    - 'NAME', 'APPLICATION TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE CASE', 'ORGANIZATION', 'INCOME AMT', 'SPECIAL CONSIDERATIONS', 'ASK_AMT'
  - What variable(s) should be removed from the input data because they are neither targets nor features?
    - 'STATUS' should be removed because it is irrelevant
  
- Compiling, Training, and Evaluating the Model

  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - There were 2 hidden layers, one with 30 neurons and one with 10 neurons in order to increase its capacity and improve its ability to learn complex patterns in the data.
  - Were you able to achieve the target model performance?
    - No, the model did not achieve greater than 75% accuracy.
  - What steps did you take in your attempts to increase model performance?
    - Changes to bin thresholds and removing certain features were tested to increase model performance.

## Summary
  - The model failed to reach 75% accuracy, proving to be a riskier model and should therefore not be used.
