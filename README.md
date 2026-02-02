# Heart Disease Prediction System

## Project Overview
This project applies Machine Learning to predict the likelihood of cardiovascular disease. By analyzing patient data (age, blood pressure, cholesterol), the system identifies high-risk individuals.



## Engineering Insight
Raw medical data is often noisy. To improve accuracy, I engineered a domain-specific feature: **Body Mass Index (BMI)**.
- **Hypothesis:** BMI correlates more strongly with heart disease than raw weight/height.
- **Result:** Adding BMI improved the model accuracy from **69.5%** to **70.4%**.

## Key Results
- **Accuracy:** 70.36%
- **Recall:** 0.70 (The model successfully catches 70% of positive cases).
- **Top Predictors:** As shown in the graph below, **BMI** is the biggest risk factor.


<img width="1490" height="801" alt="results_graph cardio" src="https://github.com/user-attachments/assets/12f54b13-ec16-4e39-8a90-e189b80fc3df" />


## Tech Stack
- **Python** (Pandas, NumPy)
- **Machine Learning** (Scikit-Learn Random Forest)
- **Data Visualization** (Seaborn, Matplotlib)
