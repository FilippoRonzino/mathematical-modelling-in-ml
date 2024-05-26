# Individual Project for ML Course
This repo contains the individual project assigned in the course of Mathematical Modelling for Machine Learning, held at Bocconi University (academic year 2023-2024).

## Project Description
The dataset is composed of 1100 samples with 30 features each. The first column
is the sample id. The second column in the dataset represents the label. There
are 2 possible values for the labels. The remaining columns are numeric
features.

Your task is the following: you should compare the performance of Logistic
Regression (implemented by sklearn.linear_model.LogisticRegression) with that of
a Random Forest (implemented by sklearn.ensemble.RandomForestClassifier). Try to
optimize both algorithms' parameters and determine which one is best for this
dataset. At the end of the analysis, you should have chosen an algorithm and its
optimal set of parameters: write this choice explicitly in the conclusions of
your notebook.

Your notebook should detail the procedure you have used to choose the optimal
parameters (graphs are a good idea when possible/sensible).

The notebook will be evaluated not only based on the final results, but also on
the procedure employed, which should balance practical considerations (one may
not be able to exhaustively explore all possible combinations of the parameters)
with the desire for achieving the best possible performance in the least amount
of time.

Bonus points may be assigned for particularly clean/nifty code and/or well-
presented results.

You are also free to attempt other strategies beyond the one in the assignment
(which however is mandatory!).

## Repository Structure
The repository is structured as follows:
- `data`: contains the dataset (train and test sets) in CSV format;
- `nb.ipynb`: contains the Jupyter notebook with the analysis;
- `predictions.txt`: contains the predictions on the test set in txt format.


