# Credit_Risk_Analysis

## Overview of the analysis:

Loans are an essential part of modern society. People borrow money to purchase homes or cars, start businesses or pursue education. Income, credit score and colleteral assets are traditional methods banks have relied on to access lending risks but today banks relies on machine learning to process a large amount of data to arrive at a single decision - whether or not to approve a loan application. In the project, we employ different methods to train and evaluate models with unbalanced classes. Specifically, we use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

We oversample the given data using RamdomOverSampler and SMOTE algorithms then a combination of over- and undersampling using SMOTEENN algorithm. Finally, BalancedRandomForestClassifier and EasyEnsembleClassifier were used to predict risks.

## Results:

### Naive Random Oversampling

The balanced accuracy test is 64 percent.

![Balanced accuracy test](https://user-images.githubusercontent.com/91093413/151721515-ad0eb385-a502-4337-a775-f9f03ece030a.png)

Figure 1: Balanced accurancy test


The precision for the high_risk is 1 percent and for the low_risk is 100 percent. The recall is 60 percent.

![Imbalanced classification report](https://user-images.githubusercontent.com/91093413/151721623-21802718-5e54-486c-b2ed-029dbdb0a97c.png)

Figure 2: Imbalanced classification report


### SMOTE Oversampling

The balanced accuracy test is approximately 65 percent.

![SMOTE balanced accuracy test](https://user-images.githubusercontent.com/91093413/151722029-ba20d393-ce29-40f0-9d25-974b4c03ef55.png)

Figure 3: SMOTE balanced accuracy test

The precision for the high_risk remains at 1 percent while the recall is now 63 percent.
![SMOTE classification report](https://user-images.githubusercontent.com/91093413/151721924-06dd7c47-094f-4528-b155-297c8b7aef90.png)

Figure 4: SMOTE classification report

### Undersampling

The balanced accuracy test is approximately 53 percent.

![Undersampling balanced accuracy test](https://user-images.githubusercontent.com/91093413/151722153-7965848c-6bbc-4176-bf4c-0d6f5db4c740.png)

Figure 5: Undersampling balanced accuracy test

The precision for the high_risk remains at 1 percent while the recall is 61 percent.
![Undersampling](https://user-images.githubusercontent.com/91093413/151722209-9cdbf6c8-4e9e-4373-85fe-08b2efbe2c6d.png)

Figure 6: Undersampling classification report


### Combination(Over and Undersampling

The balanced accuracy test is approximately 62 percent.

![Combinational balanced accuracy score](https://user-images.githubusercontent.com/91093413/151722366-58ec595f-e9fb-4f90-a72f-946cf2084c23.png)

Figure 7: Combinational balanced accuracy score

The precision for the high_risk remains at 1 percent while the recall is 69 percent.
![combination](https://user-images.githubusercontent.com/91093413/151722424-a9d3cf37-1b1a-48bd-9e1d-ab7f093bcb6d.png)

Figure 8: Combination classification report


### Balanced Random Forest Classifier

The balanced accuracy test is approximately 79 percent.

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/91093413/151722772-3b847f51-2513-40c4-8d25-3463b6b5bd17.png)

Figure 9: Balanced Random Forest Classifier

The precision for the high_risk  is 4 percent while the recall is 67 percent.
![Balanced Random Forest Classifier classification report](https://user-images.githubusercontent.com/91093413/151722840-82ad40f8-29e1-499a-9ba7-cfee6ad87317.png)

Figure 10: Balanced Random Forest Classifier classification report


### Easy Emsemble AdaBoost Classifier

The balanced accuracy test is approximately 93 percent.

![Easy Ensemble accuracy test](https://user-images.githubusercontent.com/91093413/151723051-a0137360-1788-40ce-9121-a22405bfad98.png)

Figure 11:Easy Ensemble AdaBoost Classifier accuracy score.

The precision for the high_risk  is 7 percent while the recall is 91 percent.
![Easy Ensemble accuracy test classification report](https://user-images.githubusercontent.com/91093413/151723084-b8a2af74-b055-4f5a-9865-86f5aa9d5ee4.png)

Figure 12:Easy Ensemble classification report


## Summary:

