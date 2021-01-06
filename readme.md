![alt text](https://github.com/jubertroldan/hr_job_change_ds/blob/master/geoffroy-hauwen-PSjp3kBOu9E-unsplash.jpg)

# Exploring HR Job Change for Data Scientist

## Introduction

There is a high demand for data scientist across multiple different industries. with this demand, there are a lot of movement also that may potentially occur during this period. this dataset can provide a glimpse of what is happening on the 
data scientist field which I spent some time to understand as part of the nano degree i am taking up. 

below are the highlights of the process.


## Content 

1. Pick a Dataset:
https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists/tasks?taskId=3015

2. Pose 3 questions related to business about the dataset.

	- is there a correlation between the numerical variables?<br>
	 **Ans: there seems to be no correlation between the city_development_index and training_hours**

	- Exploring using odds and WoE<br>
	 **Ans: exploring the individual odds shows low experienced would likely to move compared to highly experienced**

	- Build a model to show the tendency to move job roles as a data scientist.<br>
	 **Ans: using logistic regression as a baseline model to predict propensity - model AUC 0.75**
	

3. Prepare the Data
	- In preparing for the Data, as for many Kaggle example dataset, it has already been cleaned and structured
	the only thing i needed to work on is to identify.

4. Analyze 
	- Analysed using pandas profiling, Odds, WoE


5. Model - Logistic regression and AUC curve (0.75)


6. Visualize - Plotting the Coefficients


## Conclusion/ Summary
The analysis provided here are just example to showcase a baseline but not to solve the problem. 
if time permits - further analysis will be done to meet this requirement.

blog link here: https://jubertroldan.medium.com/exploring-the-data-hr-job-change-for-data-scientist-b7ee0fc6edfc


## Appendix / Libraries used

Libraires Used [pandas, pandas_profiling, matplotlib, sklearn] <br>

import numpy as np  <br>
import pandas as pd  <br>
import matplotlib.pyplot as plt  <br>
from pandas_profiling import ProfileReport  <br>

from sklearn.preprocessing import StandardScaler, OneHotEncoder  <br>
from sklearn.model_selection import train_test_split  <br>
from sklearn.compose import ColumnTransformer  <br>
from sklearn.pipeline import Pipeline  <br>

from sklearn.ensemble import RandomForestClassifier  <br>
from sklearn.linear_model  import LogisticRegression  <br>

## Acknowledgements
thank you for udacity for this project exercise opportunity! 
Thank you uplash 
https://unsplash.com/photos/PSjp3kBOu9E?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink

The data is available on kaggle with the link below: 
https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists/tasks?taskId=3015




