# deep-learning-challenge
For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Data Preprocessing

What variable(s) are the target(s) for your model?
The target variable is the 'IS_SUCCESSFUL' column from application_df

What variable(s) are the features for your model?
The feature variables are every other column from application_df --> this was defined by dropping the 'IS_SUCCESSFUL' column from the original dataframe

What variable(s) should be removed from the input data because they are neither targets nor features?
'EIN' column was dropped/removed, because it was neither target nor feature for the dataset.


Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the first attempt, I used 80 as layer1 and 30 as layer2 

Were you able to achieve the target model performance?
I was not able to achieve the 75% model accuracy target at first try but after including the NAME column into the features I did get %75 accuracy. 

What steps did you take in your attempts to increase model performance?
I added more layers, removed more columns, added additional hidden nodes, and switched up the activation functions associated with each layer in an attempt to achieve higher model accuracy.
Nothing seemed to help and then I included the NAME column into the features.


Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

Overall, the deep learning model was around 73% accurate in predicting the classification problem. 
Using a new model with the column NAME resulted in higher prediction accuracy. 
