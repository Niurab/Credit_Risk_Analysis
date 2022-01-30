# Credit_Risk_Analysis

## Overview of the analysis:

Loans are an essential part of modern society. People borrow money to purchase homes or cars, start businesses or pursue education. Income, credit score and colleteral assets are traditional methods banks have relied on to access lending risks but today banks relies on machine learning to process a large amount of data to arrive at a single decision - whether or not to approve a loan application. In the project, we employ different methods to train and evaluate models with unbalanced classes. Specifically, we use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

We oversample the given data using RamdomOverSampler and SMOTE algorithms then a combination of over- and undersampling using SMOTEENN algorithm. Finally, BalancedRandomForestClassifier and EasyEnsembleClassifier were used to predict risks.

## Results:

### Naive Random Oversampling

The balanced accuracy test is 67 percent.

![Balanced accuracy test](https://user-images.githubusercontent.com/91093413/151721515-ad0eb385-a502-4337-a775-f9f03ece030a.png)

Figure 1: Balanced accurancy test


The precision for the high_risk is 1 percent and for the low_risk is 100 percent. The recall is 60 percent.

![Imbalanced classification report](https://user-images.githubusercontent.com/91093413/151721623-21802718-5e54-486c-b2ed-029dbdb0a97c.png)

Figure 2: Imbalanced classification report
