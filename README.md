# 🩺 Diabetes Prediction using K-Nearest Neighbors (KNN)

## 📌 Project Overview

This project predicts whether a patient is likely to have diabetes using the **K-Nearest Neighbors (KNN)** machine learning algorithm. The project demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model training, evaluation, and performance analysis.

This project is beginner-friendly and suitable for learning classification algorithms in machine learning.

---

## 🎯 Objectives

- Analyze the diabetes dataset
- Perform data preprocessing
- Normalize numerical features
- Split the dataset into training and testing sets
- Train a K-Nearest Neighbors (KNN) classifier
- Evaluate the model using different performance metrics
- Visualize model performance

---

## 📂 Dataset

**Dataset Name:** `diabetes.csv`

The dataset contains medical information of female patients and predicts whether they have diabetes.

### Features

| Feature | Description |
|----------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age of the patient |
| Outcome | Target Variable (0 = Non-Diabetic, 1 = Diabetic) |

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📚 Machine Learning Workflow

### 1. Import Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

### 2. Load Dataset

- Read the CSV file
- Display dataset information
- Check data types

### 3. Exploratory Data Analysis (EDA)

- Inspect dataset shape
- View statistical summary
- Check missing values
- Analyze target distribution

### 4. Data Preprocessing

- Handle missing or invalid values (if any)
- Separate features and target
- Normalize features using **StandardScaler**

### 5. Train-Test Split

- Split dataset into training and testing sets
- Typical ratio: **80% Training / 20% Testing**

### 6. Model Building

- Implement **K-Nearest Neighbors (KNN)**
- Train the classifier on the training dataset

### 7. Model Evaluation

Evaluate the model using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1 Score

### 8. Visualization

The notebook includes visualizations such as:

- Class Distribution
- Correlation Heatmap
- Confusion Matrix
- Feature Distribution
- Histograms
- Boxplots

---

## 📁 Project Structure

```
Diabetes-Prediction-KNN/
│
├── KNN_Diabetes.ipynb
├── diabetes.csv

```

---

## ⚙ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Diabetes-Prediction-KNN.git
```

### Navigate to the Project Folder

```bash
cd Diabetes-Prediction-KNN
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## ▶️ How to Run

1. Clone this repository.
2. Install all required Python libraries.
3. Place `diabetes.csv` in the project folder.
4. Open `KNN_Diabetes.ipynb`.
5. Run all notebook cells in sequence.
6. Review the evaluation metrics and visualizations.

---

## 📊 Model Evaluation Metrics

The project evaluates the model using:

- ✅ Accuracy Score
- ✅ Confusion Matrix
- ✅ Classification Report
- ✅ Precision
- ✅ Recall
- ✅ F1 Score

These metrics help assess the classification performance of the KNN model.

---

## 📈 Results

The trained KNN model predicts whether a patient is diabetic based on medical attributes. Performance is evaluated using multiple metrics to ensure reliable classification.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Compare with Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier
- Build a Streamlit web application
- Deploy the model using Flask or FastAPI

---

## 📦 Requirements

Install the following packages:

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

Or install them using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

---







Happy Coding! 🚀
