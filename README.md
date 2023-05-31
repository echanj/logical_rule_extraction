# Extraction of Logical Rules with the Mushroom Dataset

Author: Eric J. Chan

Date(repo created):  26/5/2023
Date(began coding):  17/4/2023

Description:

These are codes and data where for a data science project which studies 
how well machine learning models can extract logical rules. 
This stems from my background in Chemistry where logical intuitive rules are extracted 
from in-situ laboratory experiments. 
There are also some relevant papers attached.    

This project explores the use of machine learning to extract simple logical rules for distinguishing edible and poisonous mushrooms. The dataset consists of hypothetical samples corresponding to 23 species of gilled mushrooms from the Audubon Field Guide. The objective is to investigate how well machine learning algorithms can extract simple logic, such as logical disjunction (inclusive OR). The project demonstrates that by using the features 'odor' and 'spore print color', it is possible to distinguish if a mushroom is poisonous. Data treatment includes boht non-ordinal and ordinal encoding with the 'odor' feature.

The project utilizes various models, including Logistic Regression, SVM, Naive Bayes, K-Nearest Neighbors (KNN), and Decision Trees. Scoring is done based on accuracy and F1 score, Feature importance is determined through weights with different regularization penalties, and feature selection is performed using Recursive Feature Elimination and SelectFromModel techniques. It is unclear if the logical rule for the 'odor' feature stems from human intuition, but it can be inferred from empirical observations.

   
