## **<h1 align="justify"> Credit_Risk_Analysis**
  	
---
## Overview of the project: 
<p align="justify">The objective of the project to analysis data with statistics and hypothesis testing of datasets of a automotive industry. And all the testing and analysis and visualization is written with the R programming language. <p>
	
---

<p align="justify">This project consists of four technical analysis deliverables. <p>

- Deliverable 1: Use Resampling Models to Predict Credit Risk
- Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
- Deliverable 4: A Written Report on the Credit Risk Analysis
	

### Resources
- Data Source: LoanStats_2019Q1.csv
- Software: Python 3.7 and accompanying Anaconda package, Conda 4.8.4, Jupyter Notebook

## Random Over Sampler model:
	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/ROS1.png
</p>  
	

- Calculation of the confusion matrix.
	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/ROS2.png
</p>  
		
- Imbalanced classification report

<p align="center">
	
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/ROS3.png
</p>  
	

- According to analysis provides a non-random amount of variance to the linear model of mpg.
The balanced accuracy score is 65%.
The high_risk precision is about 1% only with 62% sensitivity which makes a F1 of 2% only.
Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 68%.

	
	
	
## SMOTE model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/SM1.png
</p>  
	
- Calculation of the confusion matrix.

<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/SM2.png
</p>  

- Imbalanced classification report
	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/SM3.png
</p>  
	

- According to analysis provides a non-random amount of variance to the linear model of mpg.
	

## ClusterCentroids model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/CL1.png
</p>  
	
- Calculation of the confusion matrix	
	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/CL2.png
</p>  
	
- Imbalanced classification report
		
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/CL3.png
</p>  
	

- According to analysis provides a non-random amount of variance to the linear model of mpg.
	
## SMOTEENN model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/Smoteenn1.png
</p>  
	
- Calculation of the confusion matrix	
	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/Smoteenn2.png
</p>  
		
- Imbalanced classification report
	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/Smoteenn3.png
</p>  
	

- According to analysis provides a non-random amount of variance to the linear model of mpg.
	

## BalancedRandomForestClassifier model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/BR1.png 
</p>  
	
- Calculation of the confusion matrix
	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/BR2.png
</p>  

- Imbalanced classification report
		
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/BR3.png
</p>  
	

- According to analysis provides a non-random amount of variance to the linear model of mpg.
	
## EasyEnsembleClassifier model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/EEC1.png
</p>  
	
- Calculation of the confusion matrix	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/EEC2.png
</p>

- Imbalanced classification report
		
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Credit_Risk_Analysis/blob/main/Resources/EEC3.png
</p>  
	

- According to analysis provides a non-random amount of variance to the linear model of mpg.
