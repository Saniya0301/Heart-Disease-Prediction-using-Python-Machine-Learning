# ❤️ Heart Disease Prediction using Python & Machine Learning

This project predicts the likelihood of **heart disease** based on patient health data using **Logistic Regression** and other ML algorithms.  
It is implemented in Python and can be deployed as a **Streamlit Web App** for easy use.

---

## 📌 Features
- **Data Analysis** of the Heart Disease dataset.
- Model training with **Logistic Regression**.
- Accuracy evaluation on training & testing sets.
- **Predictive system** for new patient data.
- Ready for **Streamlit deployment** as an interactive web app.

---

## 📂 Dataset
The dataset (`heart.csv`) contains 303 patient records with the following features:

| Feature     | Description |
|-------------|-------------|
| age         | Age of the patient |
| sex         | Sex (1 = male, 0 = female) |
| cp          | Chest pain type (0–3) |
| trestbps    | Resting blood pressure (mm Hg) |
| chol        | Serum cholesterol (mg/dl) |
| fbs         | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| restecg     | Resting electrocardiographic results (0–2) |
| thalach     | Maximum heart rate achieved |
| exang       | Exercise induced angina (1 = yes, 0 = no) |
| oldpeak     | ST depression induced by exercise |
| slope       | Slope of peak exercise ST segment |
| ca          | Number of major vessels colored by fluoroscopy (0–4) |
| thal        | Thalassemia (0–3) |
| target      | 1 = Defective heart, 0 = Healthy heart |

---

## 🛠 Steps Performed

### 1️⃣ Data Preprocessing
- Loaded dataset using Pandas.
- Checked for missing values (`isnull()`).
- Explored dataset shape, data types, and statistical summary.

### 2️⃣ Splitting Data
- Split data into features (`X`) and target (`y`).
- Train-test split: **80% training**, **20% testing**.
- Stratified sampling to maintain class balance.

### 3️⃣ Model Training
- Used **Logistic Regression** from `scikit-learn`.
- Achieved:
  - **Training Accuracy:** 85.12%
  - **Testing Accuracy:** 81.96%

### 4️⃣ Prediction
- User inputs health data (13 features).
- Model outputs:
  - `1` → **Affected by Heart Disease**
  - `0` → **Healthy Heart**

Example:
```python
input_data = (37, 1, 2, 130, 250, 0, 1, 187, 0, 3.5, 0, 0, 2)


---
🏷 License

This project is open-source under the MIT License.

---
Author

SANIYA CHHABRA
---
