# Ensemble Learning Lab

This repository contains a complete worked-out lab for **Ensemble Learning** (based on *Python Machine Learning* by Sebastian Raschka and Vahid Mirjalili).

## Overview
We implement and compare multiple ensemble methods using the **Iris** and **Wine** datasets:

- **MajorityVoteClassifier** (custom implementation)
- **Bagging** (Bootstrap Aggregating) with decision trees
- **AdaBoost** (Adaptive Boosting) with decision stumps
- **Voting Classifier** (hard voting)
- **Random Forest** (bagging with feature sub-sampling)
- Comparisons with individual models (Logistic Regression, KNN, Decision Tree)

##  Objectives
- Understand ensemble learning and why it improves performance
- Implement a majority voting classifier from scratch
- Apply bagging and boosting techniques
- Compare ensembles vs single classifiers
- Perform hyperparameter tuning (Bagging & AdaBoost)
- Evaluate trade-offs: bias–variance, computational cost, interpretability


## 📝 Key Findings (Summary)
- **Majority voting** generally outperforms individual classifiers if base models are diverse.
- **Bagging** reduces variance and overfitting for high-variance learners (decision trees).
- **AdaBoost** can reduce bias but risks overfitting with too many iterations or high learning rates.
- **Random Forest** extends bagging with random feature sub-sampling → stronger diversity, usually best accuracy.
- **Trade-offs:** More estimators improve stability but increase computation. AdaBoost is sequential (slower), while bagging/RF parallelize easily.

## 📂 Outputs
All results are saved in the `outputs/` folder after running the notebook.


