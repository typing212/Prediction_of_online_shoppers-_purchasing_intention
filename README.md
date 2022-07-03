# Prediction_of_online_shoppers-_purchasing_intention
E-commerce is thriving for decades. Many e-commerce companies analyse visitor sessions on their platforms, predicting user behavior with the aim of increasing purchase conversion rates. The task in the online shopper’s intention dataset is to predict whether a user is going to make a purchase based on data from a user’s current session.


## Techniques
PCA, DT, RF, SVM, MLP, XGBoost


## Dataset
The dataset consists of 12,330 sessions. Each session was taken from a different user within a 1-year period. 
- Imbalanced dataset - resample
- 17 original features and 7 created features.
- No missing values
![image](https://user-images.githubusercontent.com/92670749/177030616-baa2a137-682d-40b5-be76-1b61deea8db9.png)


## Insights
- Duration varies among VisitorType
  New visitor spend more time on Admin pages than returned visitor. While, returned visitor is focus more on product related pages. The reason may be they are already familiar with admin. 
- Sum of page value surprisingly become smaller when getting closer to special day  
  It can be explained by multiple value source on usual days. which also suggested that we should focus more on usual days.
- Sum of page value fluctuate though year:
  We found that sum of value fluctuates a lot through different month. The second half of the year is the peak which raise to top on November. 


## Collaborators

Chen Hong

Ma Ke

Yao Chuhan

Shichao Zhang

Nanhai Zhong
