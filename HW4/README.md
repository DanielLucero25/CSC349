# CSC 349 HW4 — Heart Disease Classification

Status: both notebooks executed and checked locally. **Required Google Colab execution is pending Google sign-in.** This is not yet the final Colab-verified submission.

- `heart_disease_classification.ipynb`: eight tasks, each preceded by detailed Markdown; SVC/tree metrics and plots, training-only pipeline preprocessing, 5-fold SVC grid search, tree interpretation.
- `heart_disease_analysis.ipynb`: five detailed answers with actual saved model results.
- `heart_disease_results.json`: results exported from Task 8.

For the required Colab run, open the main notebook in Colab and run all eight cells. Save the executed notebook back to this folder. Then open the analysis notebook, upload the JSON produced by Task 8 if it is not in that runtime, run all cells, and save it here. Update this status only after both Colab runs have been verified.

Dataset: UCI processed Cleveland (303 patients, 13 predictors); diagnosis > 0 becomes disease-present class 1. Seed 42; stratified 242/61 train/test split. Numerical median imputation and StandardScaler; categorical mode imputation and OneHotEncoder. Scikit-learn version is printed in the notebook and recorded in the JSON.
