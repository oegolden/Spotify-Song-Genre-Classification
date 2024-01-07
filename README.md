# Spotify-Song-Genre-Classification
![image](https://github.com/oegolden/Spotify-Song-Genre-Classification/assets/143462618/bebae651-4d12-4a97-b2fc-3652c4593237)

#Project Overview
In this project, I used Spotify song data with features such as danceability, key, tempo, etc., and from that, I trained a model with a random forest classifier to classify songs into 114 different genres

#Packeges Used
Data Manipulation: Numpy, Pandas </br>
Data Visualization: Matplotlib, Seaborn </br>
Machine Learning: Sklearn

# Data Preprocessing
I spliced out unnecessary features and removed duplicate songs I also created a correlation heatmap amongst the features to determine whether PCA could be used and then performed PCA on then features with high covariance.
![image](https://github.com/oegolden/Spotify-Song-Genre-Classification/assets/143462618/68549219-fb2a-4ed6-ad6d-b784fa3e4c71)


# Results and Evaluation

I cross-validated across 3 models KNearestNeighbors Classifier, Decision Tree Classifier, and Random Forest Classifier. I settled upon a Random Forest Classifier. I then ran 2 Random Search Cross-Validations to find the best hyperparameters for my model, and then I ran a cross-validation for its accuracy and I also got the classification report as well as the confusion matrix. I did the same as well with a Decision tree classifier to demonstrate an alternate and faster model for genre classification.

Accuracy for Random forest classifier: 28.3%

Accuracy for Decision Tree Classifier: 19.2%
