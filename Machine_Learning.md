# What is regularization in machine learning?
` In case the question is "in layman's terms...": regularization artificially discourages complex or extreme explanations of the world even if they fit the what has been observed better. The idea is that such explanations are unlikely to generalize well to the future; they may happen to explain a few data points from the past well, but this may just be because of accidents of the sample.`
source: https://www.quora.com/What-is-regularization-in-machine-learning

# ROC versus precision-recall curve

Generally, the use of ROC curves and precision-recall curves are as follows:

## ROC curves should be used when there are roughly equal numbers of observations for each class.
## Precision-Recall curves should be used when there is a moderate to large class imbalance.
The reason for this recommendation is that ROC curves present an optimistic picture of the model on datasets with a class imbalance.

## However, ROC curves can present an overly optimistic view of an algorithm’s performance if there is a large skew in the class distribution. […] Precision-Recall (PR) curves, often used in Information Retrieval , have been cited as an alternative to ROC curves for tasks with a large skew in the class distribution.`
https://machinelearningmastery.com/roc-curves-and-precision-recall-curves-for-classification-in-python/
