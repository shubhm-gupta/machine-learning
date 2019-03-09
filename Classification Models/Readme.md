Classification is considered an instance of supervised learning, i.e., learning where a training set of correctly identified observations is available.

In this notebook, I will be implementing 4 Classification algorithms including my explaination of codes and some experiments to find out the accuracy of my models. Below are the four models that I will be implementing:

Pocket Algorithm
Quadratic Discriminant Analysis (QDA)
Linear Discriminant Analysis (LDA)
Logistic Regression

I have used a dataset for "Adult Census Income". This is a multivariate dataset consisting of 14 attributes and more than 30K samples. This is a classification problem to predict whether income exceeds $50K/yr or not based on census data. I got this data from UCI Machine Learning repository.

Dataset Source : https://archive.ics.uci.edu/ml/datasets/Adult

This notebook also includes my experiments and analysis of all these four classification algorithms. Based on the evaluation metrics, I have ranked the models based on their performance on this dataset.

I have done an additional analysis to show how these models behave for an ordinal dataset. I used "Zero-Inflated Count Data for Frequency of a Side Effect" dataset for this analysis. 

Here is the summary of evaluation metrics of my classification models:

|**Models**    | **Accuracy** | **F1 Score** | **Precision** | **Recall** | **MCC** | **ROC-AUC** |
|--------------|--------------|--------------|---------------|------------|---------|-------------|
|Pocket        |    78.65%    |0.592         |0.777          |0.587       |0.311    |0.59         |
|QDA           |    65.85%    |0.602         |0.603          |0.631       |0.232    |0.63         |
|LDA           |    64.69%    |0.493         |0.494          |0.495       |-0.011   |0.49         |
|Logistic Reg  |    78.25%    |0.730         |0.720          |0.748       |0.467    |0.75         |
