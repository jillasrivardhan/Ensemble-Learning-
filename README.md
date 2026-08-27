# Ensemble Learning

A hands-on machine learning repository focused on understanding and implementing **Ensemble Learning techniques** using real-world datasets. This project explores ensemble-based classification models such as **Random Forest** and **Gradient Boosting**, along with data preprocessing and model evaluation.

## 📌 About the Project

Ensemble Learning is a machine learning approach that combines multiple models to produce a stronger and more reliable predictive model.

This repository was created as a practical learning project to understand how ensemble algorithms work and how they can be applied to classification problems.

The projects in this repository use:

* **Titanic Dataset** for classification experiments
* **White Wine Quality Dataset** for ensemble model experiments

## 🚀 Algorithms & Concepts Covered

### 🌳 Random Forest

Random Forest is an ensemble method that combines multiple decision trees and uses their combined predictions to improve generalization and reduce overfitting.

Implemented using:

```python
from sklearn.ensemble import RandomForestClassifier
```

### 📈 Gradient Boosting

Gradient Boosting builds models sequentially, where each new model attempts to improve the errors made by previous models.

Implemented using:

```python
from sklearn.ensemble import GradientBoostingClassifier
```

## 📂 Project Contents

```text
Ensemble-Learning/
│-- Ensemble(Regression) --> California house.csv
├── Titanic.ipynb
├── Wine_Quality(random-forest).ipynb
├── Wine_Quality(gradientBoosting).ipynb
├── winequality-white.csv
└── README.md
```

> The exact filenames may vary depending on the version of the repository.

## 📊 Datasets

### Titanic Dataset

The Titanic dataset is used to explore classification and machine learning workflows.

The target variable is:

```text
survived
```

where:

* `0` → Did not survive
* `1` → Survived

The dataset contains information such as passenger class, age, sex, fare, and other passenger-related attributes.

### White Wine Quality Dataset

The White Wine Quality dataset contains physicochemical properties of white wine along with a quality score.

Important features include:

* Fixed acidity
* Volatile acidity
* Citric acid
* Residual sugar
* Chlorides
* Free sulfur dioxide
* Total sulfur dioxide
* Density
* pH
* Sulphates
* Alcohol

The target variable is:

```text
quality
```

## 🛠️ Technologies Used

* **Python**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical computing
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Scikit-learn** — Machine learning
* **Jupyter Notebook / Google Colab** — Development environment

## 🔄 Machine Learning Workflow

The notebooks follow a typical machine learning workflow:

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
```

## 📏 Model Evaluation

The models are evaluated using common classification metrics, including:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

Example:

```python
from sklearn.metrics import accuracy_score
```

and:

```python
from sklearn.metrics import classification_report
```

## 🎯 Learning Objectives

Through this repository, I practiced:

* Understanding Ensemble Learning
* Working with classification datasets
* Implementing Random Forest
* Implementing Gradient Boosting
* Preparing datasets for machine learning
* Splitting data into training and testing sets
* Making predictions
* Evaluating classification models
* Comparing machine learning approaches
* Using Scikit-learn for practical ML projects

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/jillasrivardhan/Ensemble-Learning.git
```

Navigate to the project:

```bash
cd Ensemble-Learning
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## ▶️ Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open any of the `.ipynb` files and execute the cells sequentially.

You can also open the notebooks using **Google Colab**.

## 📚 Key Takeaway

This project demonstrates how ensemble learning techniques can combine multiple learners to create more powerful machine learning models.

The repository serves as a practical reference for understanding **Random Forest, Gradient Boosting, classification workflows, and model evaluation** using Python and Scikit-learn.

## 👨‍💻 Author

**Jillasri Vardhan**

GitHub: [@jillasrivardhan](https://github.com/jillasrivardhan)

---

⭐ If you find this repository useful, consider giving it a star!
