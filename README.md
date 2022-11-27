# CaseStudy_SVM

## Summary

SVM is a supervised machine learning algorithm that works on both classification and regression problem statements.

👉 For classification problem statements, it tries to differentiate data points of different classes by finding a hyperplane that maximizes the margin between the classes in the training data.

👉 In simple words, SVM tries to choose the hyperplane which separates the data points as widely as possible since this margin maximization improves the model’s accuracy on the test or the unseen data.

![image](https://user-images.githubusercontent.com/85822284/204125115-33b87e4f-3745-4284-a10b-f15d67e7176d.png)

👉 Support vectors are those instances that are located on the margin itself. For SVMS, the decision boundary is entirely determined by using only the support vectors.

👉 Any instance that is not a support vector (not on the margin boundaries) has no influence whatsoever; you could remove them or add more instances, or move them around, and as long as they stay off the margin they won’t affect the decision boundary.

👉 For computing the predictions, only the support vectors are involved, not the whole training set.


## About the Dataset

This dataset contains information of users in a social network. Those informations are the user id the gender the age and the estimated salary. A car company has just launched their brand new luxury SUV. And we're trying to see which of these users of the social network are going to buy this brand new SUV And the last column here tells If yes or no the user bought this SUV we are going to build a model that is going to predict if a user is going to buy or not the SUV based on two variables which are going to be the age and the estimated salary. So our matrix of feature is only going to be these two columns. We want to find some correlations between the age and the estimated salary of a user and his decision to purchase yes or no the SUV.

## Evaluation of the Model:

The below Confusion Matrix evaluates the SVM Model:

![image](https://user-images.githubusercontent.com/85822284/204125147-7afa723f-f8fe-43d8-9e5f-c18e1208f904.png)


## Visualizing the Model:

**Visualize the Training Set results:**

![image](https://user-images.githubusercontent.com/85822284/204125169-dc91e9b5-0b4d-420e-9f7f-83708940f3e4.png)


**Visualize the Test Set Results:**

![image](https://user-images.githubusercontent.com/85822284/204125195-2dfc5807-0967-4e44-b987-03ba7ef49307.png)



