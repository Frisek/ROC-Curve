# ROC-Curve
This project is an exploratory analysis of a bank marketing dataset. One of the main goals of the project was to build a predictive model that could accurately classify whether or not a client would subscribe to a term deposit based on a variety of features, such as their age, job, and marital status.

To evaluate the performance of our model, we used the receiver operating characteristic (ROC) curve. The ROC curve is a graphical representation of the performance of a binary classifier at varying thresholds, and it is a useful tool for visualizing the tradeoff between sensitivity (the true positive rate) and specificity (the true negative rate).

We used Python's scikit-learn library to train and evaluate our model, and we plotted the ROC curve using the roc_curve function. We also calculated the area under the ROC curve (AUC) using the auc function, which is a common metric for summarizing the performance of a binary classifier.

Overall, our model achieved an AUC of 0.787, which indicates that it is performing better than a random classifier (which would have an AUC of 0.5) but there is still room for improvement. By adjusting the parameters of our model and exploring different feature engineering techniques, we hope to further improve its performance and provide more accurate predictions for this important banking task.
