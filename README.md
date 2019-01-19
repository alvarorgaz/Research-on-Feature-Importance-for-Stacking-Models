# Research-on-Feature-Importance-for-Stacking-Models

**Author:**

I am Álvaro Orgaz Expósito, a data science student at KTH (Stockholm, Sweden) and a statistician from UPC-UB (Barcelona, Spain).

**Abstract:** 

This repository contains the final project of the Research Methodology and Scientific Writing course in my master's degree in Data Science at KTH (Stockholm, Sweden).

Have you ever sought treatment for a mental health issue from a mental health professional? This project answers this question using state of the art Machine Learning.

The data used is a survey on mental health in the tech workplace known as *OSMI Mental Health in Tech Survey* available at Kaggle. It has 2692 responses in total (2014 and 2016) for asked questions that aimed to measure attitudes to mental health in the tech workplace and examine the frequency of mental disorders among tech workers. You can download the data of the survey at:
- 2014 at https://www.kaggle.com/osmi/mental-health-in-tech-survey
- 2016 at https://www.kaggle.com/osmi/mental-health-in-tech-2016

The main aims of this project are:
- Predict the probability of receiving treatment for a mental health issue from a mental health professional
- Use the ensembling technique Stacking for combining Supervised Machine Learning models such as: Logistic Regression, Random Forest, K Nearest Neighbors, ExtraTrees, XGBoost, LGBM, Decision Tree, AdaBoost
- Explain the prediction of the Stacking model for a new person that answers the survey using statistics on original survey data
- Provide a feature importance and instability measure for Stacking models

**Files in main folder:**
- Jupyter Notebook files with the code of the project (numerically ordered)
- *Data* folder with data and outputs of the code:
  + Survey data of 2014 in *Data2014.csv*
  + Survey data of 2016 in *Data2016.csv*
  + *data.dat* contains preprocessed survey data
  + *data_splits.dat* contains preprocessed survey data split in train, validation and test
  + *preprocessing_dictionaries.dat* contains preprocessing information of missings imputation, normalization and one hot encoding
  + *model_layer1_.dat* files containing 1st stacking layer models
  + *model_layer2_metalearner.dat* file containing 3nd stacking layer model or metalearner

**Code:** 

The project has been developed in Python using Jupyter Notebook.
