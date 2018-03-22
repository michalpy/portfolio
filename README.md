# This is my data science portfolio:

1. Kaggle: Credit Card Fraud Detection - **imbalanced classification** problem and **sampling techniques comparison**

**Summary:**
The aims of this notebook is to **deal with imbalanced dataset using sampling techniques** and **evalute performances of the classifiers** (**Logistic Regression, KNeigbors, Linear Support Vector Machine, Random Forest**). It focuses on both choosing the classifier that performance is acceptable in terms of fraud detection and **comparison** between **performance of the models** built on top of the **different sampling techniques** (**under-sampling, over-sampling and combined**). 

At the begging, the dataset is preprocessed. The feature scaling is applied, dataset is splited into training(**80%**) and test(**20%**) [while keeping **stratification** ratio]. Nextly, **23 sampling techniques** (**15** undersampling, **6** oversampling, **2** combined) are applied on the preprocessed training dataset. Notebook distinguished the division of the **sampling techniques** not only **by** their **family kind** (under-, over-, combined) but also by the **balance of the fraud class** in the obtained new datasets (balanced datasets and cleaned datasets). In the modelling chapter, **4 classifiers** are applied on **23** different training datasets. As a result, **92 models** were created. Evaluation of the models' performance is based mainly on confusion matricies, **recall** and **precision scores**. The **tradeoff (cost)** between **FP, Type I Error, precision** and **FN, Type II Error, recall** is emphasized. One of the **best models** (**benchmark**: precision **> 0.05**) that was created achieved **recall score**: **0.888** and **precision score**: **0.057** on the **test dataset**. 

In the last section, notebook visualizes **comparison between classifiers, sampling techniques** and **recall and precision scores.**

**tools:**
#jupyter #python #pandas #numpy #sklearn #imblearn #matplotlib #seaborn 

**topics:**
#data_preprocessing #feature_scaling #sampling_techniques #classification #model_evaluation #recall_and_precision #sampling_techniques_vs_classifiers_comparison


2. Kaggle: Titanic - **classification** problem 

**tools:** 
#python #jupyter #pandas #sklearn #matplotlib #seaborn

**topics:**
#data_preprocessing #data_visualization #missing_data_imputation #encoding_categorical_variables #dummy_variables #dummy_variable_trap   #feature_scaling #classification #model_evaluation #cross_validation #hyperparameters_tuning


3. In progress...
