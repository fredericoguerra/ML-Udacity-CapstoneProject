# Machine Learning for terrorism death occurrence

## Project Overview

This project outlines a Supervised Machine Learning approach to predict death occurrence in a terrorist attack around the world. Four algorithms KNN, Adaboost, Decision Tree and Random Forest classifiers are built and compared.
Accuraccy and F-score are used to evaluate the perfomance of these models and ROC curve is plotted to help the evaluation of the final model chosen and tuned. 
The final tuned Random Forest model reached an accuracy of 85.92%, F-score of 85.48% and AUC of 0.94. The top 5 most importante features to the final model is:
Weap type and subtype, number of wound, Attacck type and sucess of attack.

## Libraries
The project was done using Python 3.5 environment with the following libraries:

- Pandas
- Numpy
- Scipy
- Scikit-Learn
- Matplotlib
- Seaborn
- Visual (from Udacity)

## Data

The GTD dataset was obtained from National Consortium for the Study of Terrorism and Responses to Terrorism (START). (2018). Global Terrorism Database. Retrieved from https://www.start.umd.edu/gtd.
The database used in this project is from 1970 to 2017, containing in total 181691 rows and 135 columns. The dataset is also hosted on [Kaggle](https://www.kaggle.com/START-UMD/gtd).
