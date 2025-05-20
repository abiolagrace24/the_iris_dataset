# 🌸 Iris Flower Classification: Decision Tree & Random Forest

This notebook walks you through building machine learning models that classify flowers into species using features like petal and sepal sizes. It uses **Decision Trees**, **Random Forest**, and **Logistic Regression** on the **Iris dataset**.

---

## 📁 Dataset Used

- **iris_csv.csv** — A CSV file containing flower measurements:
  - `sepallength`
  - `sepalwidth`
  - `petallength`
  - `petalwidth`
  - `class` (species)

---

## 🛠️ Steps Covered in the Notebook

### 1. **📚 Importing Libraries**
Essential libraries for data analysis and machine learning are imported.

### 2. **📥 Load & Explore the Data**
The dataset is loaded and examined to understand structure and content.

### 3. **🔢 Convert Labels to Numbers**
Machine learning models need numbers. We convert species names into numbers using `LabelEncoder`.

### 4. **📊 Visualize the Data**
We use a **heatmap** to visualize correlation between features.

---

## ⚙️ Modeling and Evaluation

### 5. **🎯 Define Features and Target**
Split the dataset into features (`X`) and the label (`y`).

### 6. **🔁 Logistic Regression (Baseline Model)**
A simple model to test how well logistic regression performs, evaluated with a confusion matrix and classification report.

### 7. **🌳 Decision Tree (Basic)**
Train a Decision Tree on all the data. Make predictions for new flower data points.

### 8. **📦 Train-Test Split**
Split the data into training and testing sets for better evaluation.

### 9. **🌲 Decision Tree (With Train/Test)**
Train and evaluate a Decision Tree using training and testing sets.

### 10. **🌲🌲 Random Forest Classifier**
Train a Random Forest model with 10 decision trees and evaluate its accuracy.

---

## 🧪 Example Predictions
The notebook includes examples where a new flower's measurements are entered and the model predicts the species.

---

## ✅ Summary

| Model                | Accuracy (Approx.)       |
|---------------------|--------------------------|
| Logistic Regression | Good (baseline model)     |
| Decision Tree       | High (especially on training data) |
| Random Forest       | Best performance overall ✅ |

---

## 📌 Key Learnings

- How to clean and prepare data
- How to train and evaluate multiple classifiers
- The value of splitting data for testing
- Using heatmaps and reports for evaluation