# ✈️ Flight Delay Prediction Project

```
📌 Overview

Flight delays are a persistent challenge in the aviation industry, impacting customer satisfaction and increasing operational costs. This project applies machine learning and data analytics to uncover delay patterns and predict both the likelihood and duration of delays.

It is developed as part of Open Projects 2025: Analytics, under the title:
> Optimizing Air Travel: A Data-Driven Approach to Flight Delay Analysis and Predictions

```


```
🎯 Objectives

- Binary Classification: Predict whether a flight will be delayed (Yes/No).
- Regression Modeling: Estimate the expected delay duration (in minutes).
- Custom Metric:Use Operational Adjustability Index (OAI) to focus on delays that airlines can control.
- Explainable ML: Apply SHAP to interpret model predictions and extract actionable insights.

```

```
📂 Project Structure
Flight-Delay-Prediction/
│
├--flight_delay_prediction.ipynb   
│                     
├── pitch_deck.pdf                  
│
├── README.md                           
├── requirements.txt                    
├── .gitignore                           
└── LICENSE                              

```

```
🧪 Tech Stack

- Python 3.9
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, shap, streamlit

```

```
🔍 Key Features

- 📊 Exploratory Data Analysis (EDA):
  - Delay distribution trends by month, time, and day
  - Delay causes: carrier, weather, late aircraft, etc.

- 🤖 ML Models:
  - XGBoost Classifier for binary classification
  - XGBoost Regressor for delay duration prediction
  - Hyperparameter tuning with cross-validation

- ⚙️ Custom Metric — OAI:
  - Weights delay types by operational controllability
  - Guides the model to reduce actionable delays

- 🧠 Explainable AI with SHAP:
  - Global feature importance (summary plots)
  - OAI-weighted SHAP scores for actionable recommendations
```

```

📈 Model Performance

 Classification
- Accuracy:92.3%
- F1 Score: 0.89
- AUC Score: 0.94

 Regression
- MAE: 7.5 minutes
- RMSE: 12.2 minutes
- R² Score: 0.86

```

```

💡 Actionable Recommendations

- • Optimize flight scheduling to avoid peak hours and delay-prone routes  
- • Improve ground operations at high-delay airports  
- • Use SHAP + OAI to prioritize fixes for controllable delay causes  

```

```

🙋‍♂️ Author
Rahul Chauhan
B.Tech, Production & Industrial Engineering
IIT Roorkee
📧 rahul_c@me.iitr.ac.in

```
