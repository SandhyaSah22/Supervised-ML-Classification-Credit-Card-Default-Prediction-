# ML-Classification-Credit-Card-Default-Prediction

# Problem Description​

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments​

# Presentation Outline

Problem Statement​

Introduction​

Data Summary​

Methodology​

Exploratory Data Analysis​

Data Processing​

Implementing ML algorithms​

Challenges​

Conclusion​

# Introduction:​
committed using a payment card, such as a credit card or debit card. The purpose may be to obtain goods or services, or to make payment to another account which is controlled by a criminal. In recent times, the number of fraud transactions has increased drastically due to which credit card companies are facing a lot of challenges. For many banks, retaining high profitable customers is the most important business goal. Banking fraud, however, poses a significant threat to this goal. Apart from this, other ways of making fraudulent transactions are as follows:​

Manipulation or alteration of genuine cards​

Creation of counterfeit cards​

Stolen or lost credit cards​

Fraudulent telemarketing​

# Data Summary

➢ X1 -Amount of credit(includes individual as well as family credit) 

➢ X2 -Gender 

➢ X3 -Education 

➢ X4 -Marital Status 

➢ X5 -Age 

➢ X6 to X11 -History of past payments from April to September 

➢ X12 to X17 -Amount of bill statement from April to September 

➢ X18 to X23 -Amount of previous payment from April to September 

➢ Y -Default payment 

# MODEL BUILDING​

LOGISTIC REGRESSION ​

RANDOM FOREST ​

SVC​

XGBOOST ​



    #   Classifier             # Train Accuracy	    Test Accuracy        Precision Score         Recall Score      F1 Score
    
    0	Logistic Regression    0.750503	           0.752416              0.690013	             0.788382	       0.735925
    
     1	SVC	                   0.807615	           0.778095	             0.714786	             0.818384      	   0.763085
     
     2	Random Forest CLf	   0.998339	           0.837948	             0.809209	             0.858539	       0.833144
     
     3	Xgboost Clf        	   0.912001	           0.829907	             0.791958	             0.856982	       0.823188
  

From the above table we can find that xgboost classifier perform best among those models​

CHALLENGES FACED​

The data was huge and was to be handled keeping in mind that we do not miss anything which is even of a little relevance.​

Computation time.​

Getting a higher accuracy on the models.​

Carefully handling feature imbalanced data.​

Tuning of hyperparameters carefully.​

Feature engineering​

# CONCLUSION

To identify the default payment of credit card clients of huge data sets data analysis should be involved. Data analysis allows cultivation and learning based on model build, feature extraction, and various conditions that can improve the trait of customer acquirement. The four machine learning techniques mentioned can analysis the huge data set and to provide the accurate result. The boosting techniques which are included here can perform analysis for imbalanced dataset. By using Predictive analysis model for estimating the default payment and loss of extend and for predicting losses. In this paper, Machine learning technique like Logistic regression,  XGBoost, SVC and Random forest were used to detect the fraud in credit card system. Sensitivity, Specificity, accuracy and error rate are used to evaluate the performance for the proposed system. The accuracy for logistic regression, XGBoost, SVC and random forest classifier are 79%,85%,81% and 85% respectively. By comparing all the three method, found that random forest classifier is better than the logistic regression and decision tree. XGBoost provided us the best results giving us a recall of 85% percent(meaning out of 100 defaulters 85 will be correctly caught by XGBoost).


