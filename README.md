# AIInternChallenge
This project is my solution for the Linkplus IT-AI Internship Challenge – Text Classification Task.
It uses the SMS Spam Collection Dataset to classify text messages as spam or ham (not spam).

Link for the dataset: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download

Install the required dependencies: pip install pandas numpy scikit-learn nltk seaborn matplotlib

Started by data preparation: renaming columns, removed stopwords, set lowercase, clean text.

Exploratory Analysis: number of samples per category, most frequent words.

Model training: LogisticRegression, Naive Bayes, SVM, RandomForest.

Provided a script where a user can input a sentence and the model predicts its category.

Small visualization using confusion matrix.s
