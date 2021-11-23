# Credit_Risk_Analysis

## Overview

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results

#### Naive Random Oversampling results:
- Balance accuracy score was 64.8% which is considered low.
- 
![image](https://user-images.githubusercontent.com/91243905/142978580-dfd73880-062b-4c1d-b465-ed1eb70c8e84.png)


#### SMOTE Oversampling results:
- Balance accuracy score was about 66.3% which is considered low.

![image](https://user-images.githubusercontent.com/91243905/142978650-c6659648-8782-4ff9-bea6-f9b10c81bae6.png)

#### Undersampling ClusterCentroids results:
- Balance accuracy score was 66.3% which is considered low.
![image](https://user-images.githubusercontent.com/91243905/142978729-3de64449-164c-436b-9a00-0ef6c117fa68.png)



#### Combination Sampling With SMOTEENN results:
- Balance accuracy score was 64.9% which is considered low.

![image](https://user-images.githubusercontent.com/91243905/142978807-636c0e0a-2ee1-46d1-a7f1-8c26eb4d2aec.png)

#### Balanced Random Forest Classifier results:
- Balance accuracy score about 78.8%.

![image](https://user-images.githubusercontent.com/91243905/142978890-ea5a4378-90dd-42b1-aee4-8e6de9363d27.png)

#### Easy Ensemble AdaBooster Classifier results:
- Balance accuracy score was 92.5% which is high.

![image](https://user-images.githubusercontent.com/91243905/142978942-53083928-240f-43b2-9abf-8a921fa6be95.png)

## Summary 
The conclusion based on the results above, it appears that Easy Ensamble had the best performance model to predict credit risk because of its high balanced accuracy score, high precision score and recall score. 
