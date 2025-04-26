# 🌳 Decision Tree Classifier on Diabetes Dataset

This project demonstrates how to build and evaluate a **Decision Tree Classifier** to predict whether a person has diabetes based on various health-related attributes.

---

## 📊 Dataset: `diabetes.csv`

The dataset contains several medical and lifestyle-related variables:

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body Mass Index (weight in kg/(height in m)^2) |
| DiabetesPedigreeFunction | A function that scores likelihood of diabetes based on family history |
| Age | Age in years |
| Outcome | 1 = Diabetes, 0 = No Diabetes (Target variable) |

---

## 🎯 Objective

> Train and evaluate a **Decision Tree Classifier** to predict the `Outcome` based on patient health indicators.

---

## 🧠 Machine Learning Workflow

1. Load and explore the dataset
2. Perform basic data cleaning and preprocessing
3. Split the data into training and testing sets
4. Train a **Decision Tree** model using `scikit-learn`
5. Visualize the tree (optional)
6. Evaluate the model using Accuracy, Confusion Matrix, and Classification Report

---

## 📈 Model Performance

| Metric | Value (example) |
|--------|-----------------|
| Accuracy | 75% |
| Precision | 76% |
| Recall | 75% |
| F1 Score | 75% |

> (Actual numbers may vary depending on random split or tree depth settings.)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

---

## 📂 Files in the Repository

| File | Description |
|------|-------------|
| `diabetes.csv` | Dataset containing patient health records |
| `decision_tree.ipynb` | Jupyter notebook with full data analysis and model building |
| `README.md` | Project documentation (this file)

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```
2. Install required libraries:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
3.Open the notebook:
```bash
jupyter notebook decision_tree.ipynb
```
4.Run all cells to reproduce results.