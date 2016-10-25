# ML Practice

load "pair_dataset.csv" with the folling code:

    df = pd.read_csv("pair_ml_practice_dataset.csv", index_col=0)
    X,y = df.drop('label', axis=1),df['label']
            

    1) Split the data into a train and test set (30% test) with random_state=42

    2) Explore the data. Can you find any interesting or useful patterns about the data?

    3) Build your best possible model to predict the label using scikit learn. Experiment with different types of models

    4) Try to improve your model by engineering new features

    5) **May the best team win!**
