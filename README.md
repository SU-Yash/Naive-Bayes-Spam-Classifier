# Spam-Classifier
Dataset: http://archive.ics.uci.edu/ml/datasets/Spambase

Data Preprocessing: Segregated the dataset into two: (spam & not spam), generated two sets of train and test sets and then combined them to form a single set of train and test. This was done in order to ensure equal distribution of examples in the train and test sets and avoid the problem of overfitting(bias) and underfitting(variance).

Modelling: Sci-kit Learn library was used for modelling. 
  Tried two models:
      1. Naive Bayes - MultinominalNB
      2. Naive Bayes - BernoulliNB
      
  BernoulliNB had a better accuracy so it was chosen.
  
  
K-Fold Validation was done with k = 20 (Tried k = 10 and k = 20 and chose k = 20)


Final values :
Average False Positive Rate: 0.05260869565217392 
Average False Negative Rate: 0.0745219273480143 
Average Error Rate: 0.11800018821757949 


Accuracy:  0.8819998117824205





