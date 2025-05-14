# High-Cost-Member-Prediction
Built a model to identify members who are projected to incur over $100,000 in healthcare costs over the next 12 months.
This project aims to identify health plan members who are likely to incur over $100,000 in healthcare costs in the next 12 months. Early identification enables targeted interventions that may help mitigate risk, optimize care, and manage costs.
Project Deliverables are as follows
Predictive Model with Cost Estimation and Performance Evaluation - Built and trained a machine learning model to predict high-cost individuals.

Estimated future healthcare costs using supervised regression and classification techniques. Evaluated model performance using metrics such as ROC-AUC, Precision-Recall, and MAE/RMSE.

Feature Importance Analysis - Used techniques like SHAP values, permutation importance, and feature coefficients to understand key drivers. Identified clinical, demographic, and utilization-based features that strongly contribute to high costs.

Segment-Level Cost Driver Analysis - Clustered members into segments based on utilization and comorbidity patterns. Analyzed cost contributors within each segment to inform tailored intervention strategies.

Technologies Used - Python, Pandas, NumPy for data processing, Scikit-learn, XGBoost, LightGBM for modeling, SHAP, matplotlib, seaborn for explainability and visualization, Jupyter Notebook for development and exploration

Top predictive features: Prior year cost, Number of chronic conditions, Inpatient visits, Prescription drug spend

High-cost segments: Complex chronic conditions (e.g., cancer, renal failure), High emergency room utilizers.

Steps to Run the file:
1. Clone the repository
2. Install Dependencies
3. Run the Notebook
