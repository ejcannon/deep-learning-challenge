# deep-learning-challenge
Overview of the analysis: The challenge was to create a tool that can help Alphabet Soup select the applicants for funding with the best chance of success in their ventures.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
- IS_SUCCESSFUL
What variable(s) are the features for your model?
- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_AMT
- SPECIAL_CONSIDERATIONS
- ASK AMT
What variable(s) should be removed from the input data because they are neither targets nor features?
Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
- 2 layers
Were you able to achieve the target model performance?
- I was not, I got around 73% for all models
What steps did you take in your attempts to increase model performance?
- I was unable to, I increased the epoch size and removed columns in different models, and was unable to get higher than 73%

Summary: Overall the model achieved around 73% accuracy with a .55 loss after dropping more columns and increasing the epoch size. I think I could possibly have achieved a higher accuracy if I kept more columns or did a better job of cleaning the data before processiing it.
