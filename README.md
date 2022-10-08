# Supervised-Machine-Learning-Project-1-Public

Supervised Machine Learning : Classification

This dataset was collected from UC Irvine Machine Learning Repository and is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds one of 195 voice recording from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD, i.e. this is a binary classification problem. The test should have at maximum a False Negative Rate of 0.1%, that is the test sensitivity should be high, at least 0.9% as it is more important to correctly identify patients with the disease.

The is an intermediate level data analysis and is divided into 2 files -

 Supervised Learning Project- Data Wrangling.ipynb file refers to the first part of the data analysis and gives detailed intructions showing step by step on how to perform Exploratory Data Analysis(EDA). Various techniques will be performed such as "Multiple Imputation" and "BoxCox Transformation" for Outlier Treatment, "Plotting(Boxenplots, Histograms)", "Feature Selection" etc.

 Supervised Learning Project- Modelling.ipynb file refers to the second part of the data analysis and gives detailed intructions showing step by step on how to perform modelling for classifcation. Various models for Classification are shown including Gradient Boosting and Voting Classifier(Ensemble). We will also be talking about the metrics in detail used for our model for performance evaluation. We will be showing how to use threshold value with precision-recall curves and classifcation reports made with K-folds. For CV and Grid Search we will calculating multiple metrics/scores and also we will be using a custom made score function (f2_score which will be our primary metric).


Cited References:-

Max A. Little, Patrick E. McSharry, Eric J. Hunter, Lorraine O. Ramig (2008), 'Suitability of dysphonia measurements for telemonitoring of Parkinson's disease', IEEE Transactions on Biomedical Engineering (to appear).

'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection', Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM.
