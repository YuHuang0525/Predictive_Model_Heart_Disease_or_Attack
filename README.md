# Predictive_Model_Heart_Disease_or_Attack
This model aims to develop a model to predict whether one would encounter heart disease given his or her health condition and personal information.
# (For details please see pdf report)

The dataset we used contains health information from the Behavior Risk Factor Surveillance System (BRFSS) in 2015 and was
collected and cleaned by user Alex Teboul on Kaggle.This dataset has 253680 observations
and each has 22 attributes：
{'HeartDiseaseorAttack', 'HighBP', 'HighChol',
'CholCheck', 'BMI', 'Smoker', 'Stroke',
'Diabetes', 'PhysActivity', 'Fruits', 'Veggies',
'HvyAlcoholConsump', 'AnyHealthcare',
'NoDocbcCost', 'GenHlth', 'MentHlth',
'PhysHlth', 'DiffWalk', 'Sex', 'Age', 'Education',
'Income’}, among which 18 attributes are ordinal variables and 4 are discrete variables.

We tried several Machine Learning Models, i.e Factorization Machine, KNN classifier, Logistic Regression, and Balanced Random Forest.

Our model can reach 0.9093 accuracy, but with False Negative Rate being 0.9218.
We then try decrease our FNR with several different approaches, and eventually reach FNR = 0.1107, along with approximately 0.70 accuracy.

