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
bash
git clone https://github.com/your-username/cardiovascular-risk-prediction-ml.git
cd cardiovascular-risk-prediction-ml

##  2️⃣ Install Dependencies
pip install numpy pandas matplotlib seaborn scikit-learn
3️⃣ Run Notebook
Open .ipynb file in:
Jupyter Notebook OR
Google Colab
🩺 Example Prediction
Input:
Age: 59
Smoking: No
Exercise: High
Diet: Moderate
Family History: No

Output:
Risk Score: 15.4
Risk Level: LOW ✅
##  Visualizations Included
Feature Distribution
Output Distribution
Correlation Heatmap
Model Performance Charts
Actual vs Predicted Graph
Feature Importance
Patient Risk Dashboard

##  Key Insights
Strong correlation between Reading & Writing equivalent health metrics
Lifestyle factors significantly impact cardiovascular risk
Exercise and diet reduce risk
Smoking and family history increase risk

##  Future Enhancements
Real medical dataset integration
Web app (Streamlit / Flask)
Deep Learning model
Real-time health monitoring
Mobile app integration

##  Disclaimer

This project is for educational purposes only.
It is not a medical diagnosis tool.

##  Author

Atul Anand
BCA (Hons)
Amity University, Noida

## ⭐ Support

If you find this project helpful, don’t forget to star ⭐ the repository!
