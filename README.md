# Wine-Project

#Readme

Applying Machine Learning algorithms on Wine Quality data available at UCI Machine Learning repository, this project tests various techniques to predict Color & Quality of wine from its chemical components.

Data: https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/

Thus, the inspiration of the project is to challenge the efficiancy of sommeliar by applying Machine Learning.

For convenience and uniformity only the best 5 quality of wine are included for analysis from the dataset.


The analysis proceeds in below steps:

Importing data for Red/White color wine, randomized amongst each other to spew a sample size between range of 2000 - 3000.

Data exploration technique - scatter plot & correlation plot are utilized to better understand the correlation of components of wine with each other.

Followed by Regression plot to understand the interaction betwenn most proabable features.

Splitting data into Test/Train datasets for random forest modelling

Random Forest Trees model is applied on Quality as Target and Color as target, The model predicts the Color with an accuracy of 93% however fails miserably in predicting the Quality of wine.

Highly Correlated variables are removed from the dataset & the problem of correctly classifying the wine in its quality if targeted.

Displaying violen plots to further understand the interaction of Quality of wine with the obvios parameters.

Normalizing the data, divding data in features and target & plotting parallel co-ordinated plot to reveal hidden trend in the features -- Does not reveal any significant relation.

Creating test/train splits on Normalized data and applying Linear Discriminant Analysis.

LDA returns a accuracy of 68% on Train dataset while a prediction accuracy of 70% on Testing dataset.

Applying Random Forest on Normalized data with a limitation of 100 trees, shows a high accuracy of 76% is achieved at 8th,19th trees. As the accuracy does not increase significantly after the 20th tree it is appropriate to run the modelling only for 20 trees.


Conclusion:
A sommelier's salary can range between $65k to $175k yearly, similarly with skill a sommelier can accurately predict correctly 4/7 times to 6/7 wines. While the prediction considering only the chemical components of the wine is getting it right 76% of times.
There is enough scope of improvement of the models accuracy power.

