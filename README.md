# Text-classification-of-emails
Personal project on classifying spam vs legitimate emails

Question: can we predict if an email is spam or ham?

I read the text dataset of emails, tokanized them, and cleaned them
Then compared lemmatizers and stemmers to get to the root of each word.
And finally I vectorized them to prepare them for ML classifiers.

ML pipeline:
feature engineering: creating and evaluating some features that may help in classification
Classifier candidates: Random Forest and Gradient Boosted Machine
Cross_validation to tune hyperparameters of the models as well as selecting the best vectorizer
Model selection: cross_validation on the test data set and choosing among the models with the highest performance


1) reading_semi_structured_text
2) exploring
3) preprocessing
4) stemming_lammitizing
5) vectorizing
6) feature_engineering
7) ml_classifier_rf
8) ml_classifier_gbm
9) model_selection


Note: I should try simpler classifiers first such as logistic regression, svm classification, and KNN
Note: I should try creating a lot more features
Note: in the hyper-parameter tuning, I should try a bigger range.
Note: final step needs some modifications.
