# Credit_Risk_Analysis

# Purpose 
The purpose of the project was to develop a Supervised machine learning model to aid in the credit analysis review of application for loan. An accurate model can aid in timing, resourcing and efficiency of the lion screening process. 

# Descriptions 
The project contains two Jupiter note books and utilized Loan data sourced from Lending Club, a peer to peer company. The data was split into test and train sets and scaled for consumption.
	Notebook titled Credit_risk_resampling is a resampling analysis of the data. The notebook cleans the data and then runs it though two over sampling, one under sampling and one combined sampling algorithms to determine which algo yields the most accurate results based on imbalanced classification reports.  

Over sampling - Nave Over Sampling and Smote Over Sampling 
Under Sampling - Cluster Centroids.
Combined Sampling - Smoteen

	Notebook titles Credit_Risk_ensemble referenecs the same data set but trains two ,machine learning models (Random Forest & EasyEnsemble)to help reduce bias and determine if the accuracy improves. 

## Sampling Results 
 
Over sampling - of the two models tested Smote performed the best yielding a F1 score of 81% with 99% accuracy and 69% recall. The F1 score was roughly 5% better than the Nave model. 

Under sampling - under sampling with Cluster Centroids gave equivalent results to Smoteen and did not improve any of the metrics  in the classification report.  


Combined sampling - produced a good precision score but performed the worst of all sampling models in recall and resulted in a 56% F1 score. 



## Modeling Results 

Of the two  Machine learning models, Radome Forest produced the best results with 99% in accuracy, precessions and F1 score.  

##Conclusion - based on the comparative analysis of the data set the best performers  are Smoteen sampling and Random Forest Modeling. 

Reference Jupiter notebooks for more detail on classification repots. 

