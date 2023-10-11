# Predicting income bracket with Random Forest Classifier

In this project, I will be using a dataset containing census information from UCI’s Machine Learning Repository. By using this census data with a random forest, I will try to predict whether or not a person makes more than $50,000.

The original data set is available at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/census+income). 

Some of the input and output features of interest are:

- age: continuous
- workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
- education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool
- race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black
- sex: Female, Male
- capital-gain: continuous
- capital-loss: continuous
- hours-per-week: continuous
- native country: discrete
- income: discrete, >50K, <=50K
