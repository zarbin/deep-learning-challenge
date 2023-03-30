# Deep Learning Challenge - Homework 21
UTA DataViz Bootcamp <br>
03/29/2023

# Summary

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The dataset provided by the bank contains 77,536 records with seven key indicators.

* Size of the loan
* Interest rate on the loan
* Borrower's income
* Debt_to_Income ratio
* The number of of accounts that the borrower uses regularly
* Derogatory marks on the borrower's credit report
* The borrower's total debt
* loan status ('1' indicates that the borrower defaulted, a '0' indicates a healthy loan)


# Work and Findings

Data Preview

![image](https://user-images.githubusercontent.com/36682023/227839168-06bdc7af-7381-4630-9eeb-97e286232813.png)


## Create a Logistic Regression Model with the Original Data

Machine Learning Model **1**, Logistic Regression **using raw data**:

  Balanced Accuracy Score 0.9520479254722232

    Confusion Matrix results
          True positive:  18663   
          False positive: 56
          True negative:  563
          False negative: 102
