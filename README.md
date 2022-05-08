# Neural_Network_Charity_Analysis
## Overview
Using deep machine learning - neural networks to assist a large charitable organization to predict which organization to donate to with high a successful outcome. Different neural network models were tested for its optimization with a goal to achieve an accuracy prediction over 75%.

## Resources
* Data Source: charity_data.csv
* Software: Python 3.7.11, Google Colab Notebook 

## Results
*Data Preprocessing
* The `IS_SUCCESSFUL` served as the target variable of the deep learning neural network model because it provided binary data on whether the donation was used effectively.
* `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`, `ORGANIZATION`, `STATUS`, `INCOME_AMT`, `SPECIAL_CONSIDERATIONS`, and `ASK_AMT` served as the features for the model.
* The columns `EIN` and `NAME` were removed from the input data because they were neither target or features and did not contribute to the model's prediction accuracy to being more robust.



Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
