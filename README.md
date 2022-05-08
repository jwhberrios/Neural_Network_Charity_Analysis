# Neural_Network_Charity_Analysis
## Overview
Using deep machine learning - neural networks to assist a large charitable organization to predict which organization to donate to with high a successful outcome. Different neural network models were tested for its optimization with a goal to achieve an accuracy prediction over 75%.

## Resources
* Data Source: charity_data.csv
* Software: Python 3.7.11, Google Colab Notebook 

## Results
Data Preprocessing
* The `IS_SUCCESSFUL` served as the target variable of the deep learning neural network model because it provided binary data on whether the donation was used effectively.
* `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`, `ORGANIZATION`, `STATUS`, `INCOME_AMT`, `SPECIAL_CONSIDERATIONS`, and `ASK_AMT` served as the features for the model.
* The columns `EIN` and `NAME` were removed from the input data because they were neither target or features and did not contribute to the model's prediction accuracy to being more robust.



Compiling, Training, and Evaluating the Model
* The number of neurons were increased (optimization #1) and the number of hidden layers were increased (optimization #2) as a means to make the prediction model more robust with the dataset. The number of epochs were increased (optimziation #3) to increase the iteration of the data. All 3 adjustments did not increase the prediction accuracy of the model to go above 75%.


## Summary
The prediction accuracy of the deep learning neural network model did not increase to or exceed 75%. Since the target variable is a binary data, the `Random Forest Classifier` model may be a suitable alternate model to use along with its ability to train large datasets.
