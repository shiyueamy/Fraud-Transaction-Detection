# Fraud Detection on Credit Card Transaction
### Introduction
Fraud is a rising billion-dollar business. According to the PwC global economic crime survey of 2018, there are 49% of the 7,200 companies who participated had suffered fraud. Fraud could be complicated in the real world business, which means we need to spend a significant amount of time planning and preparing before we start to throw fancy machine learning algorithms on it.   
### Workflow 
In this project, I performed EDA on a heavily imbalanced dataset contains 28 anonymized features and compared 7 popular classification models for differnet business objectives. For more insights, please check my DataPrep python notebook listed above( if it is not loading well, please visit: https://nbviewer.jupyter.org/github/shiyueamy/Fraud-Transaction-Detection/blob/master/DataPrep_for_Fraud_Detection.ipynb)
Generally, please consider Random Forest for wider degree of comprehensiveness or Logistic Regression for a higher precision.
### Model Evaluation Metrics 
*Precision* evaluates how sure our model in detecting fraud transactions as *recall* shows how many fraud cases our model is able to detect. In general, the more precise our model is, the less cases it will be able to detect. For heavily imbalanced distribution like this, we would love to take a look at *F1-score* as a measure of precision-recall tradeoff.
It seems like that recell score is the metric that could help us catch the most fraud transactions, however, if we predict a fraud which turns out not to be, is not a massive problem compared to the opposite for company’s side, it might hurt some innocent customers’ feelings.
