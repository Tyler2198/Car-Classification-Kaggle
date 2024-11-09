# Car-Classification-Kaggle 🚗 🚕 🚙
This is a popular classification problem from Kaggle. The given data set requires classification of car class. The project includes different models and comparison between them. I have included some data processing regimes coupled with different classification models such as Logistic Regressions, Decision Trees and Random Forests.

Overall, Decision Trees and Random Forests seem to yield superior results in terms of Test accuracy. Results are superior also when considering the confusion matrix report. This is due to the fact that the sample is unbalanced in targets, with class 1 having a support of 19 cars, versus class 2 with 300 + samples. Logistic Regressions tend to suffer under such regimes of samples. We can see this when applying weight restrictions that drastically improve precision and recall and F1-Scores across the board and across class 1.

Still, Decision Trees and Random Forests seem to be less vulnerable to such structures thus bringing better results from the start.
The data set favors a label encoder instead of one-hot-encoding for the categorical variables. One-hot-encoding determines a sparse matrix of data when dealing with a restricted support, thus penalizing trees and forests. 

Overall, a Decision tree model determines the best results, with a test accuracy of 0.971 and 0.97 in weighted average Precision, Recall and F1-Score. These three metrics are also improved for class 1, with an F1-score of 0.84.
