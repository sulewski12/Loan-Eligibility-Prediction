# Loan Eligibility Prediction

### Project description and motivation

The goal of the project is to come up with the most efficient model predicting the loan eligibility status based on the data provided by the customers.
That's a very common issue among insurance companies, whereas among all industries, insurance field has one of the largest use of data science and analytics methods.<br>
The predictor's outcome is binary 'YES" or 'NO' - prediction of the possibility of giving a certain customer a loan.
While working on that project I could get a proper, basic overview of the challenges the insurance companies face and what variables influence the outcome the most.

### Data description

The dataset I used was taken from https://www.kaggle.com/ninzaami/loan-predication.<br>
It contains 615 records with 12 customer details stored in columns.
The columns' names are explicit enough to give an idea what values are stored there, therefore I do not attach any additional file with columns' names clearance.

### EDA, Model implementation and taken steps

A detailed explanation what steps I've taken throughout the project is included within the jupyter notebook.

### Further work and improvements

- Deeper feature engineering with an emphasis on new features creation and development of combinations between existing ones.
- Wider range of grid search on the chosen classifiers, plotting RocAucCurves for each of them what would give a better insight in precision/recall pattern.
- Usage of more advanced regression techniques like stacking or blending, testing different combinations of classifiers on the VotingClassifier (soft and hard).

### Helpful resources

While working on this project I found below mentioned sources very helpful:

- https://www.kaggle.com/datafan07/top-1-approach-eda-new-models-and-stacking
- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, II Edition, O'Reilly, Aurelien Geron, 2019
