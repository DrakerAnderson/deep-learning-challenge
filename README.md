# deep-learning-challenge

## Data Preprocessing

# What variable(s) are the target(s) for your model?
- I used the column 'IS_SUCCESSFUL' as my target for my model
# What variable(s) are the features for your model?
- The features of my model were 'APPLICATION_TYPE', 'CLASSIFICATION', 'STATUS', 'INCOME_AMT', 'ASK_AMT',
# What variable(s) should be removed from the input data because they are neither targets nor features?
- I took out USE_CASE, ORGANIZATION, SPECIAL CONSIDERATIONS since they are categorical.

## Compiling, Training, and Evaluating the Model
# How many neurons, layers, and activation functions did you select for your neural network model, and why?
- I used 43 input features, 2 layers, with 8 and 5 neurons. I picked small numbers since I was only doing 5 epochs.
# Were you able to achieve the target model performance?
- no
# What steps did you take in your attempts to increase model performance?
- I reduced the amount of columns being used, increased the layers to 3 with larger amounts of neurons (100, 30, 10) with 100 epochs and it didn't make any improvement.
