# SHAP Explorer: Explainable AI with SHAP

## Project Overview
This project demonstrates the application of **SHAP (Shapley Additive exPlanations)** for explainable AI (XAI) across **regression** and **binary classification** tasks. The project provides both **global** and **local** explanations for model predictions using advanced SHAP visualization techniques.  

By leveraging SHAP, we aim to interpret and understand how features contribute to the predictions of machine learning models, increasing transparency and trust in AI systems.

---

## Datasets Used
1. **Regression Task**
   - **Dataset:** Boston Housing Dataset
   - **Description:** Contains information about housing values in suburbs of Boston. Features include crime rate, average number of rooms, accessibility to highways, and more.
   - **Target Variable:** Median value of owner-occupied homes (`MEDV`)

2. **Binary Classification Task**
   - **Dataset:** Breast Cancer Wisconsin Dataset
   - **Description:** Contains features computed from digitized images of fine needle aspirate (FNA) of breast masses.  
   - **Target Variable:** Diagnosis (`malignant` or `benign`)

---

## Models Used
- **Regression:** XGBoost Regressor (`XGBRegressor`)
- **Binary Classification:** Random Forest Classifier (`RandomForestClassifier`)

The models were trained on their respective datasets, and SHAP values were computed to explain individual predictions and overall feature importance.

---

## SHAP Explanations
### 1. Local Explanations
Local explanations describe the impact of each feature on individual predictions.  
Visualizations include:
- **Force Plots:** Show feature contributions for a single prediction.
- **Waterfall Plots:** Highlight cumulative contributions of features for a single instance.
- **Decision Plots:** Track feature contributions across multiple instances.

### 2. Global Explanations
Global explanations provide an overall understanding of feature importance across the dataset.  
Visualizations include:
- **Summary Plots:** Display feature importance and effect across all instances.
- **Dependence Plots:** Show the effect of a single feature across the dataset, considering interaction with other features.
- **Feature Importance Plots:** Rank features based on their contribution to the model’s predictions.

---

Some of the explanations are discussed below.

<img width="1171" height="625" alt="image" src="https://github.com/user-attachments/assets/ca467727-fe01-4457-96b0-e387f038dcbf" />

<img width="1157" height="602" alt="image" src="https://github.com/user-attachments/assets/e40e5747-afe4-4b06-b4bf-5121bb84f419" />

<img width="1142" height="610" alt="image" src="https://github.com/user-attachments/assets/b781af60-a446-49f4-b6e1-3d529716bf7d" />

<img width="1147" height="597" alt="image" src="https://github.com/user-attachments/assets/ee0e462e-2598-4aac-a3ee-168144afcb67" />

<img width="1140" height="612" alt="image" src="https://github.com/user-attachments/assets/7b22ea16-dc9c-459c-9951-2e2d251d3782" />

<img width="1150" height="635" alt="image" src="https://github.com/user-attachments/assets/5a960bbe-f1db-4a5b-98f2-338e5bca59f3" />

<img width="1091" height="513" alt="image" src="https://github.com/user-attachments/assets/8d70f998-e313-4588-a5cb-2de4c9d8943e" />


## Key Highlights
- Both **regression** and **classification** tasks are analyzed with SHAP.
- Advanced SHAP plots allow visual understanding of model behavior.
- Helps in identifying the most impactful features influencing predictions.
- Provides transparency and interpretability to complex ML models.

---


