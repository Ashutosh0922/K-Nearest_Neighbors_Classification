# K-Nearest_Neighbors_Classification

# K-Nearest Neighbors (KNN) Classification - Iris Dataset

## 📌 Objective
The goal of this project is to understand and implement the **K-Nearest Neighbors (KNN)** algorithm for solving classification problems using Python.

---

## 🧰 Tools & Libraries Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## 📂 Dataset
- **Name**: Iris Dataset
- **Source**: Provided CSV file `Iris.csv`
- **Features**:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
  - Species (Target Variable)

---

## ✅ Tasks Covered

### 🔹 Task 1: Load and Normalize the Dataset
- Loaded data using Pandas
- Normalized features using `MinMaxScaler`

### 🔹 Task 2: Train KNN Model
- Used `KNeighborsClassifier` from scikit-learn
- Split data into training and test sets

### 🔹 Task 3: Experiment with Different K Values
- Tried multiple values for `k` (e.g., 1, 3, 5, 7)
- Observed accuracy changes

### 🔹 Task 4: Evaluate the Model
- Printed **Accuracy Score**
- Displayed **Confusion Matrix** using `seaborn.heatmap`

### 🔹 Task 5: Visualize Decision Boundaries
- Reduced features to 2D
- Used a meshgrid to visualize decision regions for `k=3`
- Encoded class labels for plotting

---
