# Scott Smith Capstone Propsal
# Machine Learning Engineer Nanodegree
# Loan Defaults Using Lending Club Data


## Data Location

This project uses Lending Club data as published on Kaggle:
https://www.kaggle.com/wordsforthewise/lending-club#accepted_2007_to_2018Q3.csv.gz

The project uses the file: accepted_2007_to_2018Q2.csv.gz

In the final project, I will provide a partial pre-processed file, along with a program to use this source data to create the preprocessed data.


## Environments

This project will use standard python libraries using Python 3.6
All other necessary python files will be provided with the project submission.

The following libraries are used:

python==2.7.15
numpy==1.15.4
pandas==0.24.0
sklearn==0.20.2
matplotlib==2.2.3
seaborn==0.9.0
pathlib==1.0.1
mlxtend==0.13.0

mlstend Installation: http://rasbt.github.io/mlxtend/installation/


## Running the Models (Start with 3 of 5)

This is a 5-step process. Steps 1 and 2 prepare the data and steps 3 to 5 are different models.

1. LendingClubCleanSourceData (1of5).ipynb
   Do the first pass of data cleaning, reducing the data set to the segments needed
   Takes raw file, accepted_2007_to_2018Q3.csv.gz,
   outputs: LendingClub2017_2018BasicPrep.csv.gz

2. LendingClubFeatureEngineer (2of5).ipynb
   Do feature engineering and pre-processing to get the data 'model ready'
   Takes: LendingClub2017_2018BasicPrep.csv.gz
   Outputs: LendingClub2017_2018FeatureReady.csv.gz

3. LendingClubBaseModes  (3of5).ipynb
   Takes: LendingClub2017_2018FeatureReady.csv.gz (this file is provided)
   Run Classifiers with default hyperparameters. 
   Run GridSearchCV on Classifiers to tune hyperparameters. 

4. LendingClubEnsemble  (4of5).ipynb
   Takes: LendingClub2017_2018FeatureReady.csv.gz (this file is provided)
   Run Ensemble methods with best models, from step 3 to find the best base estimators,
  

5. LendingClubStacking (5of5).ipynb
   Takes: LendingClub2017_2018FeatureReady.csv.gz (this file is provided)
   Run Stacking methods with best models, from step 3 to find the best classifiers and meta-classifier.
   
   Using: http://rasbt.github.io/mlxtend/user_guide/classifier/StackingClassifier/




