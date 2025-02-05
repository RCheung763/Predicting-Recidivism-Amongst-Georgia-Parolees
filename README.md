# Recidivism

## Abstract
Utilizing recidivism data from the Georgia Department of Community Supervision [3],
supervised models were created to learn what variables could lead to recidivism and test if models
could predict recidivism with high accuracy. Unsupervised learning was run to determine if clusters
could answer any questions toward optimal variables. While 4 key principal components and 11 K-
Means clusters were identified this would only explain the usefulness of continuous variables not the categorical variables in the
dataset. Following this analysis of the continuous variables, Gradient Boosting and Support Vector
Machine (SVM) models were created. The binary classification model of the Gradient Boosting
yielded a test accuracy rate of 73.6%, however it also yielded a false positive rate of 39.6%. A
multi-class classification gradient boosting model was also run which was used to indicate if a
person would reoffend and if so would they reoffend in one, two or three years. Both the binary and
multi-class classification models indicated similar top variables for determining recidivism. The top
two variables were percentage of days employed and jobs per year. Gang affiliation, average
number of days on parole between drug tests and supervision score also ranked high in the
models. Of the three SVM models run (linear, radial basis and polynomial kernels). A focus was made on not only accuracy but importantly reducing the rates of false positive.
