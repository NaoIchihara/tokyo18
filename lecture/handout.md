# Summary of Key Concepts

## Model Fit
- In statistical modelling, we want to estimate f in Y = f(X) + e, where Y is the response (outcome), X is a set of features (predictors), and e is the error.
- To prevent overfitting, we split the data into **training** and **testing** sets. We develop the model on the training set, then evaluate its performance on the testing set.
- We choose an error (loss) function appropriate for the prediction task, eg. mean squared error (sum of residuals squared divided by sample size) for regression (quantitative Y), sum of misclassifications for classification (categorical Y).

## Random Forest
- Random forest is an ensemble method combining predictions from multiple decision trees to reduce uncertainty.
- A decision tree is essentially a series of branching rules based on the predictors.
- To build a tree, an algorithm called recursive binary splitting is used. A stopping criterion is specified, eg. minimum node size or maximum tree depth.
- At each branching point, only a random subset of all predictors are considered as potential split candidates. This is done to decorrelate the trees.

## Support Vector Machine
- asd

## Cross-validation
- asd

## Others
- asd
