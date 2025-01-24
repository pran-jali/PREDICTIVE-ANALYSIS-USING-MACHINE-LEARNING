# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
PERFORM ANALYSIS ON A LARGE DATASET USING TOOLS LIKE PYSPARK OR DASK TO DEMONSTRATE SCALABILITY. Name=Pranjali Pradeep Shinde Company=Codetech IT Solutions Intern ID=CT08HVO Domain=Data Analyst Duration=30th December 2024 to 30th January 2025 Mentor= Neela Santosh Task 2=BUILD A MACHINE LEARNING MODEL (E.G.REGRESSION OR CLASSIFICATION) TO PREDICT OUTCOMES BASED ON A DATASET.
Logistic regression is a classification algorithm, used when the value of the target variable is categorical in nature. Just like Linear regression assumes that the data follows a linear function, Logistic regression models the data using the sigmoid function. As it happens, a sigmoid function, defined as follows, produces output having those same characteristics and thus ensures that the model output always falls between 0 and 1
Based on the number of categories, Logistic regression can be classified as:
Binomial: target variable can have only 2 possible types: “0” or “1” which may represent “win” vs “loss”, “pass” vs “fail”, “dead” vs “alive”, etc.
Multinomial: target variable can have 3 or more possible types which are not ordered(i.e. types have no quantitative significance) like “disease A” vs “disease B” vs “disease C”.
Ordinal: it deals with target variables with ordered categories. For example, a test score can be categorized as:“very poor”, “poor”, “good”, “very good”. Here, each category can be given a score like 0, 1, 2, 3.
A Decision Tree is a simple representation for classifying examples. It is a Supervised Machine Learning where the data is continuously split according to a certain parameter. Decision Tree consists of :
Nodes : Test for the value of a certain attribute.
Edges/ Branch : Correspond to the outcome of a test and connect to the next node or leaf.
Leaf nodes : Terminal nodes that predict the outcome (represent class labels or class distribution).
The Random Forest Classifier is a set of decision trees from randomly selected subset of training set. It aggregates the votes from different decision trees to decide the final class of the test object. It is an ensemble tree-based learning algorithm.

K-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems.

The KNN algorithm assumes that similar things exist in close proximity. In other words, similar things are near to each other. KNN captures the idea of similarity (sometimes called distance, proximity, or closeness) with some mathematics we might have learned in our childhood— calculating the distance between points on a graph.

For finding closest similar points, you find the distance between points using distance measures such as Euclidean distance, Hamming distance, Manhattan distance and Minkowski distance. Euclidean distance is a popular and familiar choice. KNN has the following basic steps:
Calculate distance
Find closest neighbors
Classification report is another way to evaluate the classification model performance. It displays the precision, recall, f1 and support scores for the model.
Precision can be defined as the percentage of correctly predicted positive outcomes out of all the predicted positive outcomes. It can be given as the ratio of true positives (TP) to the sum of true and false positives (TP + FP).

So, Precision identifies the proportion of correctly predicted positive outcome. It is more concerned with the positive class than the negative class.

Mathematically, precision can be defined as the ratio of TP to (TP + FP).

Recall
Recall can be defined as the percentage of correctly predicted positive outcomes out of all the actual positive outcomes. It can be given as the ratio of true positives (TP) to the sum of true positives and false negatives (TP + FN). Recall is also called Sensitivity.

Recall identifies the proportion of correctly predicted actual positives.

Mathematically, recall can be given as the ratio of TP to (TP + FN). True Positive Rate is synonymous with Recall and can be given as the ratio of TP to (TP + FN).

f1-score
f1-score is the weighted harmonic mean of precision and recall. The best possible f1-score would be 1.0 and the worst would be 0.0. f1-score is the harmonic mean of precision and recall. So, f1-score is always lower than accuracy measures as they embed precision and recall into their computation. The weighted average of f1-score should be used to compare classifier models, not global accuracy.
Receiver Operating Characteristics (ROC) Curve
Another tool to measure the classification model performance visually is ROC Curve. ROC Curve stands for Receiver Operating Characteristic Curve. An ROC Curve is a plot which shows the performance of a classification model at various classification threshold levels.
The ROC Curve plots the True Positive Rate (TPR) against the False Positive Rate (FPR) at various threshold levels. True Positive Rate (TPR) is also called Recall. It is defined as the ratio of TP to (TP + FN). False Positive Rate (FPR) is defined as the ratio of FP to (FP + TN).
ROC AUC stands for Receiver Operating Characteristic - Area Under Curve. It is a technique to compare classifier performance. In this technique, we measure the area under the curve (AUC). A perfect classifier will have a ROC AUC equal to 1, whereas a purely random classifier will have a ROC AUC equal to 0.5.
So, ROC AUC is the percentage of the ROC plot that is underneath the curve.

