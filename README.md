# Credit-Card-Fraud-Detection
Anonymized credit card transactions labeled as fraudulent or genuine. A Kaggle Challenge


Dataset
The datasets contains credit card transactions over a two day collection period in September 2013 by European cardholders. There are a total of 284,807 transactions, of which 492 (0.172%) are fraudulent.

The dataset contains numerical variables that are the result of a principal components analysis (PCA) transformation. This transformation was applied by the original authors to maintain confidentiality of sensitive information. Additionally the dataset contains Time and Amount, which were not transformed by PCA. The Time variable contains the seconds elapsed between each transaction and the first transaction in the dataset. The Amount variable is the transaction amount, this feature can be used for example-dependant cost-senstive learning. The Class variable is the response variable and indicates whether the transaction was fraudulant.

The dataset was collected and analysed during a research collaboration of Worldline and the Machine Learning Group of Université Libre de Bruxelles (ULB) on big data mining and fraud detection.




About the dataset

Exploratory Data Analysis

Model Building
Logistic Regression (LR)
Decision Tree (DT)
Random Forest (Boostrap Ensemble of DT)


Model Selection
Considerations for Model Selection

Inspiration
Identify fraudulent credit card transactions.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.
