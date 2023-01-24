# Playground-Series-Season-3-Episode-4

The dataset has been taken from [here](https://www.kaggle.com/competitions/playground-series-s3e4/data)

The dataset for this competition (both train and test) was generated from a deep learning model trained on the Credit Card Fraud Detection. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

Note, this base dataset for this competition was much larger than previous Tabular Tuesdays datasets, and thus may contain more artifacts than the last three competitions.

Files

    train.csv - the training dataset; Class is the target
    test.csv - the test dataset; your objective is to predict Class
    sample_submission.csv - a sample submission file in the correct format



About The Dataset:

    Id - A unique Id for each row.
    Time - Number of seconds elapsed between this transaction and the first transaction in the dataset
    V1-V28 - Features with dimensionality reduction to protect user identities and sensitive features(v1-v28)
    Amount - Transaction amount
    Class - Target Class (1 for fraudulent transactions, 0 otherwise)

