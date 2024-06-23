# EDA-Project-on-STEG-Dataset

## Project Overview

### Abstract:
The main goal of this project is to make you feel familiar with Supervised Learning
Algorithms like Regression and Gradient Boosting algorithms along with practicing
more Exploratory Data Analysis techniques and developing your ML intuition.

### Description:
The Tunisian Company of Electricity and Gas (STEG) is a public and 
non-administrative company, it is responsible for delivering electricity and gas across
Tunisia. The company suffered tremendous losses in the order of 200 million Tunisian
Dinars due to fraudulent manipulations of meters by consumers.
Using the client’s billing history, the challenge aims to detect and recognize
clients involved in fraudulent activities.
The solution will enhance the company’s revenues and reduce the losses caused by
such fraudulent activities.

### Data Problem:
Building a model that will help classify which customer is likely to commit fraud by
that saves the company from making losses.

## Dataset
### Data Issues:
- Imbalanced Dataset with around 20% for class 1 and 80% for class 0
- Training set and test set each have a different distribution
- The dataset is not normally distributed 
- Training and test sets have different amounts of each class in it as training includes around 8% of class 1 and 92% of class 0 while the test set includes 50% for each class

### Data Preprocessing
- Removing mistaken values, null values, and useless features like client ID, etc 
- Normalizing the following features as they’re the ones that need normalization: 
  - Consommation_level_1
  - Consommation_level_2
  - Consommation_level_3
  - Consommation_level_4
  - Old_index
  - New_index
- Merge training and testing sets and then split them again to solve different distribution issues  
- Apply undersampling to solve imbalance on the whole dataset issue
- Applying label smoothing to improve model performance potentially.





