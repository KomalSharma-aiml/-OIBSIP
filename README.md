# 🔗 OIBSIP Data Science Internship Task-1
Machine Learning project to classify Iris flowers using Logistic Regression, KNN, and Decision Tree.

#  🔗 Iris Flower Classification using Machine Learning

An end-to-end Machine Learning project that classifies Iris flowers into **Setosa, Versicolor, and Virginica** using 
multiple classification algorithms. The project covers the complete ML workflow, including Exploratory Data Analysis (EDA), 
feature scaling, model training, evaluation, cross-validation, and prediction.

## 🔗 Project Summary

The objective of this project is to predict the species of an Iris flower based on four numerical features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The notebook demonstrates how different classification algorithms perform on the Iris dataset and compares their results using 
multiple evaluation techniques.

## 🔗 Dataset

* **Source:** Scikit-learn `load_iris()`
* **Total Samples:** 150
* **Features:** 4 numerical features
* **Classes:** 3 (Setosa, Versicolor, Virginica)

## 🔗 Tech Stack:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 🔗 Project Workflow

1. Load and inspect the Iris dataset.
2. Perform Exploratory Data Analysis (EDA).
3. Create visualizations including Pairplot, Boxplots, and Correlation Heatmap.
4. Split the dataset into training and testing sets.
5. Apply **StandardScaler** for distance-based learning.
6. Train multiple machine learning models.
7. Compare model accuracy.
8. Evaluate using Cross-Validation, Confusion Matrix, and Classification Report.
9. Make predictions with probability scores.
10. Interpret feature importance using Decision Tree.

## 🔗 Exploratory Data Analysis

The notebook includes:

* Dataset overview
* Statistical summary
* Pairplot visualization
* Boxplot analysis
* Feature Correlation Heatmap

These visualizations help understand feature relationships and class separation before training the models.

## 🔗 Machine Learning Models

The following models were trained and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

## 🔗 Additional Techniques Implemented

* StandardScaler
* 5-Fold Cross Validation
* Decision Tree Visualization
* Prediction Probability
* Feature Importance Analysis

## 🔗 Model Evaluation

The models were evaluated using:

* Accuracy Score
* Cross-Validation Score
* Confusion Matrix
* Classification Report
* Accuracy Comparison Chart

The notebook compares all three models to identify their performance on unseen data.

## 🔗 Key Features of This Project

* Complete EDA before model training.
* Feature scaling using StandardScaler.
* Comparison of multiple classification algorithms.
* Cross-validation for more reliable evaluation.
* Decision Tree visualization for interpretability.
* Prediction demo with probability scores.
* Feature importance analysis.

## 🔗 Key Learnings

Through this project, I practiced:

* Exploratory Data Analysis (EDA)
* Data visualization with Seaborn and Matplotlib
* Feature scaling using StandardScaler
* Supervised Machine Learning
* Model comparison and evaluation
* Cross-validation
* Decision Tree interpretation
* Predicting new samples with confidence scores

### 🔗 How to Run

1. Clone the repository.
2. Navigate to the project directory.
3. Install the required dependencies using:
   pip install -r requirements.txt
4. Open `Iris_Flower_Classification.ipynb` in Jupyter Notebook or Google Colab.
5. Run all cells sequentially to reproduce the analysis and classification results.
