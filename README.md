# Employees-Attritbutes-Analysis-Model

This project involves analysis of Employee Attributes using KNN classifier, Random Forest classifier, Gradient Boost classifier and MLP.

The first step is to make all the necessary imports.
Then we loaded dataset into a dataframe.
We are then checking the no. of rows and columns present in the dataset.

After that, we have used info(), describe() function to get the inner insights of the dataset.
We are checking if there is any missing value or duplicate values present in the dataset so that we can handle it accordingly. As there is no such value present, there is no need to handle any such values.

We then check for the columns which have data in the form of integers and try to visualise it using matplotlib library.
The same is done for categorical columns.

To get the correlation of each feature in the dataset, corr() function is used. Then we visualise different distribution using seaborn library.

We then started with Data Preprocessing, splitting the dataset into training and testing and finally evaluation of particular model.

Metrices which are used for evaluation of algorithms used includes confusion matrix, classification report(which involves precision, recall, f1 score, support). Confusion matrix is used because it presents the different outcomes of the prediction and results of a classification problem in a tabular format  and helps visualize its outcomes in a better way. Classification Report provides a better understanding of the overall performance of our trained model.

The models with their corresponding accuracies are:

KNN classifier: 88.20%

Random Forest classifier: 100.0%

Gradientboost classifier: 91.02%

MLP: 85.93%

Confusion Matrix depicts that Random Forest Classifier is correct to a large extent and at the same time it is having the score of 100% in model evaluation, so it is the model that can be deployed for Employee Attribute Analysis.
