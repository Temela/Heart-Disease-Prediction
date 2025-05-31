
# 🫀 Heart Disease Prediction Using K-Nearest Neighbors

<p align="center">
  <img src="https://raw.githubusercontent.com/Temela/Heart-Disease-Prediction/main/banner.png" alt="Heart Disease Prediction Banner" />
</p>

Predicting the likelihood of heart disease can help reduce preventable deaths through early detection and intervention. This project uses a K-Nearest Neighbors (KNN) model to predict heart disease based on clinical and lifestyle indicators.

---

## 🎯 Objective

- Explore a real-world medical dataset on cardiovascular health.
- Use Exploratory Data Analysis (EDA) to uncover insights.
- Train and evaluate a K-Nearest Neighbors model.
- Reflect on ethical and human-centered AI principles in medical applications.

---

## 📄 Dataset

- **Source:** [Kaggle – Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Features include:**
  - Age, Sex, ChestPainType, RestingBP, Cholesterol, FastingBS, RestingECG
  - MaxHR, ExerciseAngina, Oldpeak, ST_Slope
  - HeartDisease (target variable)

📁 `data/heart.csv`

---

## 🔍 Exploratory Data Analysis (EDA)

- Distribution of heart disease across genders and age groups.
- Correlations between cholesterol, blood pressure, and risk.
- Visual breakdown of categorical features like chest pain type and ECG results.

📓 See: [`Heart Disease.ipynb`](Heart%20Disease.ipynb)

---

## 🤖 Machine Learning Approach

- **Model used:** K-Nearest Neighbors (KNN)
- **Evaluation metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- **Steps:**
  - Data normalization
  - Train-test split
  - Hyperparameter tuning (best k-value)

---

## 📈 Key Findings

- **Chest Pain Type** and **ST Slope** are highly predictive of heart disease.
- Patients with higher resting blood pressure and cholesterol show increased risk.
- The model performs with good accuracy but is limited by dataset size.

---

## 💡 Human-Centered & Ethical Considerations

- **Inclusive Design**: Medical data models must avoid biased assumptions based on sex, age, or socioeconomic proxies.
- **Data Dignity**: Although this is a public dataset, the project avoids making rigid conclusions about real-world patients.
- **Explainability Matters**: KNN was selected for its interpretability, offering clearer decisions than opaque black-box models.
- **Responsible AI**: This project serves as a proof-of-concept. In real applications, decisions should be augmented by professionals—not replaced by algorithms.

> Predictive healthcare models should support—not replace—compassionate care.

---

## 🛠 Tools Used

- Python (Pandas, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook
- GitHub

---

## 🧪 Reproducibility

To run this notebook:

```bash
git clone https://github.com/Temela/Heart-Disease-Prediction
cd Heart-Disease-Prediction
jupyter notebook Heart\ Disease.ipynb
```

---

## 📃 License

This project is open-source under the MIT License.
