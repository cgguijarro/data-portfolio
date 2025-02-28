# Objective
The primary goal of this analysis is to develop a predictive model to accurately detect fraudulent credit card transactions. Given the high cost and risk associated with fraud, this model aims to:

- Minimize financial loss: By identifying potential frauds early, credit card companies can reduce losses and prevent unauthorized charges.
- Enhance customer protection: Detecting fraudulent transactions in real time can protect customers from being charged for purchases they did not make.
- Address class imbalance: Due to the highly unbalanced nature of the dataset (frauds constitute only 0.172% of transactions), the analysis will focus on performance metrics such as the Area Under the Precision-Recall Curve (AUPRC), which is more meaningful than simple accuracy in this context.

Note: The dataset originates from PCA-transformed features, making direct interpretability challenging, the emphasis here is on robust predictive performance to flag fraud effectively.

# Dataset
This analysis utilizes the Credit Card Fraud Detection dataset from Kaggle (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data), which comprises credit card transactions made by European cardholders in September 2013.
