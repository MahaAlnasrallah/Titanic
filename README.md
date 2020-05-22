# Titanic
Titanic Survival Model 
## Overview
this I built a decision tree by hand, that at each stage, picked the features that were most correlated with survival. Lucky for me, this is exactly how decision trees work! In this lab, i will do this much quicker by implementing a decision tree in sklearn.
## Dataset | titanic_data.csv

these are the various features present for each passenger on the ship:
|Feature | Description |
|---|---|
Survived | Outcome of survival (0 = No; 1 = Yes)
Pclass | Socio-economic class (1 = Upper class; 2 = Middle class; 3 = Lower class)
Name | Name of passenger
Sex | Sex of the passenger
Age | Age of the passenger (Some entries contain NaN)
SibSp | Number of siblings and spouses of the passenger aboard
Parch | Number of parents and children of the passenger aboard
Ticket | Ticket number of the passenger
Fare | Fare paid by the passenger
Cabin | Cabin number of the passenger (Some entries contain NaN)
Embarked | Port of embarkation of the passenger (C = Cherbourg; Q = Queenstown; S = Southampton)

## Improving the model
high training accuracy and a lower testing accuracy. We may be overfitting a bit. so, 
and try to specify some parameters in order to improve the testing accuracy, such as:

max_depth The maximum number of levels in the tree.
min_samples_leaf The minimum number of samples allowed in a leaf.
min_samples_split The minimum number of samples required to split an internal node.
