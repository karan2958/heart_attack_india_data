# Heart Attack India Data Analysis 🚑

**Hello Readers**  
I sourced this dataset from Kaggle and performed a full exploratory and predictive analysis in **Heart Attack India.ipynb**. In the first section, you’ll see how to load and **clean** the data—an essential step before any modeling. Next, I generated a variety of visualizations (Bar Chart, Histogram, Heatmap, Scatter Plot, ROC Curve) to uncover patterns. Finally, I built a logistic regression model to predict heart attack risk, evaluating metrics like accuracy, precision, recall, and ROC–AUC.

---

## 🔍 About

This project analyzes heart attack risk factors using patient data drawn from a Kaggle dataset. It explores demographic, clinical, and exercise-related variables to understand their influence on heart disease incidence in an Indian context, and then builds a predictive model to classify risk.

---

## 📂 Dataset

The analysis uses **heart_attack_prediction_india.csv**, which contains the following features:

- **age**: Patient age in years  
- **sex**: Gender (0 = female, 1 = male)  
- **cp**: Chest pain type (0–3)  
- **trestbps**: Resting blood pressure  
- **chol**: Serum cholesterol in mg/dL  
- **fbs**: Fasting blood sugar > 120 mg/dL (0 = false, 1 = true)  
- **restecg**: Resting ECG results (0–2)  
- **thalach**: Maximum heart rate achieved  
- **exang**: Exercise-induced angina (0 = no, 1 = yes)  
- **oldpeak**: ST depression induced by exercise relative to rest  
- **slope**: Slope of the peak exercise ST segment (0–2)  
- **ca**: Number of major vessels (0–3) colored by fluoroscopy  
- **thal**: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)  
- **target**: Heart attack (1 = yes, 0 = no)

---

## 🧹 Data Cleaning & Preparation

1. **Loaded** the CSV into a pandas DataFrame  
2. **Explored** missing values and duplicate records  
3. **Handled** nulls via imputation or removal, as appropriate  
4. **Encoded** categorical variables and standardized formats  
5. **Scaled** numeric features in preparation for modeling

---

## ✨ Key Questions & Findings

1. **Age groups at risk:** _[Insert your insights on age vs. heart attack incidence here.]_  
2. **Gender differences:** _[Summarize male vs. female risk rates.]_  
3. **Cholesterol correlation:** _[Highlight how cholesterol levels relate to the target.]_  
4. **Exercise impact:** _[Discuss trends in max heart rate and exercise‐induced angina.]_  
5. **Predictive performance:** Our logistic regression model achieved **X% accuracy** with an ROC AUC of **Y%**.  

*(Replace X and Y with your actual results from the notebook.)*

---

## 📊 Visualizations

I leveraged these chart types to tell the story:

- **Bar Chart** for categorical distributions (e.g., chest pain types)  
- **Histogram** for continuous features (e.g., age, cholesterol)  
- **Heatmap** of feature correlations  
- **Scatter Plot** showing relationships (e.g., age vs. max heart rate)  
- **ROC Curve** illustrating model discrimination power

---

## 🤖 Modeling & Evaluation

- Trained a **Logistic Regression** classifier with Scikit-learn  
- Evaluated performance using accuracy, precision, recall, F1-score, and ROC AUC  
- Applied **train-test split** and **cross-validation** for robustness

---

## 🛠 Tech Stack & Dependencies

- **Language:** Python 3.8+  
- **Notebook:** Jupyter  
- **Libraries:**  
  - `pandas`, `numpy`  
  - `matplotlib`, `seaborn`, `plotly`  
  - `scikit-learn`, `openpyxl`  

Install all dependencies with:
```bash
pip install -r requirements.txt
