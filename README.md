# ❤️ Cardiovascular Risk Prediction using Machine Learning

This project uses **Machine Learning** to predict multiple cardiovascular health parameters and an overall **risk score** based on patient lifestyle and medical factors.

It combines:
- 📊 Exploratory Data Analysis (EDA)
- 🤖 Multi-output Machine Learning
- 📈 Advanced visualizations
- 🩺 Real-world health insights

---

## 🎯 Objective

- Predict multiple health parameters simultaneously:
  - Stenosis (% blockage)
  - Artery Diameter
  - Cholesterol
  - Blood Pressure
  - Heart Rate
  - BMI
  - Risk Score
- Analyze how lifestyle factors impact heart health
- Provide a risk level classification (LOW / MODERATE / HIGH)

---

## 📊 Dataset

- Synthetic dataset (medically realistic ranges)
- Generated using NumPy
- 300 patient records
- Features include:
  - Age
  - Smoking
  - Exercise
  - Diet
  - Family History

---

## 🚀 Features

- Synthetic healthcare dataset generation
- Full Exploratory Data Analysis (EDA)
- Multi-output regression model
- Correlation analysis with heatmap
- Model evaluation (MAE & R² score)
- Feature importance analysis
- Custom patient prediction system
- Risk level classification
- Visual dashboards:
  - Histograms
  - Heatmaps
  - Scatter plots
  - Bar charts
  - Risk profile chart

---

## 🧠 Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🤖 Machine Learning Model

- **Algorithm:** Random Forest Regressor
- **Type:** Multi-Output Regression
- **Evaluation Metrics:**
  - Mean Absolute Error (MAE)
  - R² Score

---

## 📈 Model Performance

- Average R² Score ≈ **0.55**
- Best predicted parameter:
  - Risk Score (R² ≈ 0.81)

---

## ▶️ How to Run

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/cardiovascular-risk-prediction-ml.git
cd cardiovascular-risk-prediction-ml
