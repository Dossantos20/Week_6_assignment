# Week_6_assignment
ANA 505 week 6 assignment

**Accuracy rate results**:
SVM accuracy: 97.3%
  The model correctly predicted all setosas, however it got 2 versicolor and 2 virginica wrong - achieving 146/150 correct predictions
  The model doesn't divide the data in subsets, instead the model helps visualizing and identifying the best features for its prediction. After selecting both petal features, we can train and assess the prediction results
  
K Means accuracy: 88.6%
  The model uses a unsupervised learning approach by clustering the data set. In this example, the model removes the iris classification and afterwards "creates" 3 new categories. Category 1 had 100% match with setosa, cat 2 had a 92.3% match with virginica and cat 3 had a 77% match with versicolor

C50 accuracy: 93.3%
  The model correctly predicted all setosas, however it got 1 versicolor and 2 virginica wrong - achieving 42/45 correct predictions
  In the C50 model, the data is split into each iris category and each category is further divided into train and test data sets. The model then assess the data set features and build multiple decision trees for its training component - and finally the model is used to predict the results
