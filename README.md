# Ensemble Learning Lab

This repository contains a complete worked-out lab for **Ensemble Learning** (based on *Python Machine Learning* by Sebastian Raschka and Vahid Mirjalili).

## 📘 Overview
We implement and compare multiple ensemble methods using the **Iris** and **Wine** datasets:

- **MajorityVoteClassifier** (custom implementation)
- **Bagging** (Bootstrap Aggregating) with decision trees
- **AdaBoost** (Adaptive Boosting) with decision stumps
- **Voting Classifier** (hard voting)
- **Random Forest** (bagging with feature sub-sampling)
- Comparisons with individual models (Logistic Regression, KNN, Decision Tree)

## 🎯 Objectives
- Understand ensemble learning and why it improves performance
- Implement a majority voting classifier from scratch
- Apply bagging and boosting techniques
- Compare ensembles vs single classifiers
- Perform hyperparameter tuning (Bagging & AdaBoost)
- Evaluate trade-offs: bias–variance, computational cost, interpretability

## 🚀 Running in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook: **Ensemble_Learning_Lab.ipynb**.
3. Run all cells (**Runtime → Run all**).
4. Generated outputs will be stored in the `outputs/` folder:
   - ROC AUC results (`part1_roc_auc.csv`)
   - Decision boundary plots (`part2_decision_boundaries.png`)
   - AdaBoost error convergence plot (`part3_adaboost_error_convergence.png`)
   - Classifier comparison table (`part4_comparison.csv`)
   - Hyperparameter tuning summary (`part4_tuning_summary.txt`)

## 📊 Deliverables
- ✅ Colab-ready Jupyter notebook: **Ensemble_Learning_Lab.ipynb**
- ✅ Visualization plots (decision boundaries, AdaBoost error)
- ✅ CSV tables (performance comparisons)
- ✅ Tuning summary text file
- ✅ **Report (PDF + HTML)**: summarizing methods, results, and analysis
- ✅ README.md (this file)

## 📝 Key Findings (Summary)
- **Majority voting** generally outperforms individual classifiers if base models are diverse.
- **Bagging** reduces variance and overfitting for high-variance learners (decision trees).
- **AdaBoost** can reduce bias but risks overfitting with too many iterations or high learning rates.
- **Random Forest** extends bagging with random feature sub-sampling → stronger diversity, usually best accuracy.
- **Trade-offs:** More estimators improve stability but increase computation. AdaBoost is sequential (slower), while bagging/RF parallelize easily.

## 📂 Outputs
All results are saved in the `outputs/` folder after running the notebook.

---
**Author:** _Your Name_  
**Course/Assignment:** Ensemble Learning Lab
