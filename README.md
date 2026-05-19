# ⚽ FIFA 21 Player Market Value Predictor
An End-to-End Data Science and Machine Learning project that handles raw football player data, builds high-accuracy predictive models for market value, and provides interactive business intelligence insights.

---

## 📌 Project Overview
This project focuses on transforming raw sports data into actionable insights for scouting and financial evaluation. By leveraging historical player attributes from FIFA 21, the pipeline cleans the data, engineers key performance features, and deploys multiple Machine Learning and Deep Learning models to accurately predict a player's market value. Additionally, an interactive Power BI dashboard is integrated to provide visual analytics for stakeholders.

## 🛠️ Tech Stack & Tools
* **Language:** Python (Google Colab)
* **Data Libraries:** Pandas, NumPy, Scikit-learn
* **ML/DL Frameworks:** CatBoost, XGBoost, Gradient Boosting, Keras/TensorFlow (ANN)
* **Business Intelligence:** Power BI (Data Mapping & Visual Analytics)

---

## 📈 Machine Learning Workflow
1. **Data Loading & Exploration (EDA):** Analyzed player distributions, nationalities, and core features.
2. **Data Cleaning & Feature Selection:** Handled missing values, dropped irrelevant columns, and selected critical features (`Age`, `Overall`, `Potential`, `Pace`, `Shooting`, `Passing`, `Dribbling`, `Defending`, `Physical`).
3. **Feature Scaling & Splitting:** Applied scaling to handle varying attribute ranges and split data into training/testing sets.
4. **Model Training & Evaluation:** Trained and compared multiple models using regression metrics ($R^2$ and MAE).

---

## 🏆 Model Performance & Results
The models achieved outstanding accuracy, capturing both linear and highly complex non-linear patterns:

| Model | $R^2$ Score | Mean Absolute Error (MAE) |
| :--- | :--- | :--- |
| **Gradient Boosting** | **99.47%** | **~ €1.68M** |
| **Artificial Neural Network (ANN)** | **90.26%** | **~ €583K** |

*Note: Gradient Boosting proved to be the most robust model for general market value estimation, while the ANN captured deeply complex structural player patterns.*

---

## 📊 Power BI Dashboard & Visual Insights
An interactive dashboard was designed to bridge the gap between technical models and non-technical scouts/managers. 
* **Geographic Mapping:** Visualized player talent distribution globally.
* **Scouting Analytics:** Enabled quick filtering by club, nationality, potential, and value.
* **Model Presentation:** Clear graphs highlighting the most impactful attributes driving player value.

### 📷 Dashboard
![Power BI Dashboard](dashboard.png)
---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone [https://github.com/mohamed7saad7/FIFA21-Market-Value-Predictor.git](https://github.com/mohamed7saad7/FIFA21-Market-Value-Predictor.git)
