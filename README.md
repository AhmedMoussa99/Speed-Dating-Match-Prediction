# Speed-Dating-Match-Prediction
predict the outcome of a specific speed dating session based on the profile of two people, so we can implement a recommendation system to better match people in speed dating events
# Problem Formulation:
-This is a binary classification task. Containing a tabular dataset called ("Speed Dating Match Prediction") and the excepected goal from it to predict the outcome of a specific speed dating session based on the profile of two people.

-It has 192 features as input (information about the dating session) and as output, we are going to predict the probability (0-1, float) that the dating session will lead to a successful match. So we can implement a recommendation system to better match people in speed dating events.

-The data mining function that we need in this problems is binary classification and predictions models for output.

-The challenges are that the dataset is clean, but has a lot of missing values. The strategy for missing value replacement has to be tuned. And choosing the best feature selection method for selecting the appropriate features. As well as, this dataset is highly unbalanced (mostly unmatched).

-The impact of the product on real life help making better match people in speed dating events. Because it is normal for a person to try more than one date until he finds a suitable partner so it quick this process by providing better matching.

-The life cycle of data mining model to be able to predict the probability of successful match is divided to several steps:

# Problem understanding

-Data collection.

-Data preparation.

-Modeling. (We use 2 Different Classifiers)

-Evaluation.

# What is an ideal solution?

-The ideal solution is to make the appropriate preprocessing on the important columns that will be important and positively affect predicting the probability of successful match.

# What is the experimental protocol used and how was it carried out? What preprocessing steps are used?

-The experimental protocol used is (The Cross-validation) because it is usually the preferred method as it gives the model the opportunity to train on multiple train-test splits. This gives a better indication of how well the model will perform on unseen data.

-The general procedure is as follows:

Shuffle the dataset randomly. Split the dataset into k groups For each unique group: Take the group as a hold out or test data set Take the remaining groups as a training data set Fit a model on the training set and evaluate it on the test set Retain the evaluation score and discard the model Summarize the skill of the model using the sample of model evaluation scores Preprocessing steps that I need:

1)Handling missing values.

2)Handling numerical features.

3)Handling catigorical features.

4)Scaling and Normlization data.
