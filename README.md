# deep-learning-challenge
Analysis of investment data using deep learning models

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?

The target is the 'Is-successful' column.

What variable(s) are the features for your model?

The features include:

name, application type, affiliation, classification, use_case, organization, income, special considerations, status, and ask amount

What variable(s) should be removed from the input data because they are neither targets nor features?

The 'EIN' category and 'name' category. These two fields have no numerical values that would impact the model.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Thismodel is using 3 hidden layers. This quantity of layers seems to increase the performance of the model. The first layer uses a 'relu' activation while the rest use 'sigmoid.' Data had to be re-evaluated to improve accuracy. 'Name' was restored, which improved accuracy.

Were you able to achieve the target model performance?
Yes

What steps did you take in your attempts to increase model performance?
Restoring the 'NAME' column and converting them to data points increased the performance. This plus the addition of the third layer allowed the model to reach the target.

Summary: Summarize the overall results of the deep learning model.

Overall, the accuracy is above the 75% target threshold. The model is able to accurately classify values in the dataset with ~78% accuracy.
