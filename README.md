# 🧠 Logistic Regression Binary Classification

## 📁 Dataset
We used the **Breast Cancer Wisconsin Dataset** provided as `data.csv`. The target variable is `diagnosis`:
- `M` (Malignant) = 1
- `B` (Benign) = 0

## 🔍 Objective
To build a **binary classifier** using **Logistic Regression** that predicts whether a tumor is malignant or benign based on features from the dataset.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🔢 Steps Performed

### 1. Data Preprocessing
- Dropped unnecessary columns (`id`, `Unnamed: 32`)
- Encoded categorical target (`M/B`) to numeric (`1/0`)
- Checked for missing values

### 2. Feature Scaling & Splitting
- Applied `StandardScaler` to normalize feature values
- Split data into 80% training and 20% testing sets

### 3. Model Training
- Trained a `LogisticRegression()` model on the scaled training data

### 4. Model Evaluation
- Generated **Confusion Matrix**, **Precision**, **Recall**, and **ROC-AUC Score**
- Plotted **ROC Curve**

### 5. Threshold Tuning
- Adjusted classification threshold (e.g., 0.4 instead of 0.5)
- Evaluated the impact on precision and recall

### 6. Sigmoid Function Plot
- Visualized the sigmoid curve used in logistic regression

---

## 📊 Results

| Metric       | Value   |
|--------------|---------|
| Precision    | XX.XX   |
| Recall       | XX.XX   |
| ROC-AUC      | XX.XX   |

*(Replace XX.XX with your actual results)*

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/logistic-regression-task.git
   cd logistic-regression-task
