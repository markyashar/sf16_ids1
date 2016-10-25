Download the following file

``` bash
wget https://archive.ics.uci.edu/ml/machine-learning-databases/00228/smsspamcollection.zip
```

If you unzip it, you will see a tab seperated file called SMSSpamCollection.

The first column is the label, the second column is some text recieved by SMS. 

keep a 30% holdout set, seed=42

Take 1:
1. Use Count Vectorizer to convert Text to features
2. Build a Model
3. Report Accuracy, Confusion Matrix in Slack Channel

Take 2:

1. Build a simple pipeline with a count vectorizer feeding into a model of your choice
2. Report Classificication Report, Confusion Matrix
3. Plot ROC Curve
4. Plot Precision / Recall Curve for Detecting Spam
5. Can you choose a different Cutoff to get a Higher Accuracy