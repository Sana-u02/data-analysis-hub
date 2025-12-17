# 🎓 Academic Performance Analysis & Prediction



## Project Goal
To use the **CatBoost Classifier** to build a high-performance model that predicts student academic outcomes (Pass/Fail) and quantifies the influence of key demographic and external factors.

## Data Source
The dataset used for this analysis was obtained from **Kaggle**:
[Students Academic Performance Dataset](https://www.kaggle.com/datasets/sadiajavedd/students-academic-performance-dataset)

##  Key Technologies
* **Model:** CatBoostClassifier
* **Libraries:** Pandas, Scikit-learn, Seaborn

##  Performance & Findings

* **Model:** CatBoostClassifier (utilizing categorical features)
* **Accuracy:** 86%
* **Critical Issue:** The model showed **0% Recall** for the 'Fail' class. This indicates a severe **class imbalance** problem, causing the model to overfit and simply guess "Pass" for all students.




