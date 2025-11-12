# Kaggle Playground: Feature Reduction Experiment

This notebook explores the effect of feature quantity versus model performance.

Starting from a dataset with a large number of additional engineered features, I gradually reduced the feature set to identify which variables truly contribute to predictive accuracy.

## Goal
To understand how feature selection influences model stability and generalization in a regression/classification task from the Kaggle Playground Series.

## Approach
1. Initial stage – maximal feature set, including all engineered and derived columns.  
2. Iterative reduction – step-by-step removal of weak or redundant features using correlation analysis, feature importance, and validation results.  
3. Evaluation – comparison of model metrics (MAE / RMSE / accuracy, depending on the task) after each reduction step.

## Insights
- More features do not necessarily mean better performance.  
- A smaller, well-chosen subset can improve consistency and reduce overfitting.  
- Clear feature structure simplifies further model tuning.

## Files
- `road-accidents.ipynb` – main notebook with full workflow.  
- `requirements.txt` – dependencies (optional).

Part of my ongoing exploration of Kaggle Playground competitions and practical ML experimentation.