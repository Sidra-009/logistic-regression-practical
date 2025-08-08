# 🌸 Logistic Regression – Iris Dataset (Binary Classification)

This project demonstrates the practical implementation of **Logistic Regression** for binary classification using the **Iris dataset**. The focus is on classifying between *Iris-versicolor* and *Iris-virginica* using Scikit-learn and evaluating model performance with cross-validation and hyperparameter tuning.

---

## 📂 Project Structure

- `logistic_regression.ipynb` – Jupyter notebook with complete implementation
- `README.md` – Project overview and usage guide

---

## ✅ Features

- Load and filter the Iris dataset for binary classification  
- Map categorical species to numerical labels  
- Split data into training and testing sets  
- Implement and tune Logistic Regression using `GridSearchCV`  
- Evaluate model using classification report and accuracy  
- Visualize data using Seaborn pair plots  
- Display correlation matrix

---

## 🛠️ Tools & Libraries

- Python  
- NumPy  
- Pandas  
- Seaborn  
- Matplotlib  
- scikit-learn  

---

## 🧪 Model Training & Tuning

- **Model**: Logistic Regression  
- **Tuning Parameters**:
  - `penalty`: `l1`, `l2`, `elasticnet`
  - `C`: Regularization strength
  - `max_iter`: Maximum iterations
- **GridSearchCV** used with `cv=5` for cross-validation

---

## 📊 Evaluation

- **Metrics**:
  - Accuracy Score
  - Classification Report (Precision, Recall, F1-Score)
- **Best Parameters**: Displayed using `best_params_`
- **Best Score**: Shown using `best_score_`

---

## 🖼️ Visualizations

- Pair Plot colored by species
- Correlation matrix

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/logistic-regression-iris.git
cd logistic-regression-iris
