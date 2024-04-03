# Neural Network Report

## Overview of the analysis: Explain the purpose of this analysis.
    - The purpose of this analysis was to select applicants for funding with the best chances of success for a nonprofit foundation. 

## Results: Using bulleted lists and images to support your answers, address the following questions:

### Data Preprocessing

What variable(s) are the target(s) for your model?
-   the 'IS_SUCCESSFUL' column

What variable(s) are the features for your model?
-   everything other than the 'IS_SUCCESSFUL' column

What variable(s) should be removed from the input data because they are neither targets nor features?
-   no variables are fully removed but several are encoded from         categorical values into numeric values.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
-   i chose -- layers, -- neurons for the first layer and -- neurons for the second layer. i chose these parameters since they seemed to return the best results in terms of loss and accuracy.

Were you able to achieve the target model performance?
-   

What steps did you take in your attempts to increase model performance?
-   i tried several different combinations of amounts of layers and neurons to maximize the accuracy score and loss. after several iterations of this process i found a combination that satisfied the accuracy requirements.

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

-   Overall, my final model returned an accuracy score of -- and a loss of --. Based on these stats, i -- recommend this model.