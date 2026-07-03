# Customer Retail Data Classification Using Machine Learning

## 📌 Project Overview

This project demonstrates the implementation and comparison of three supervised Machine Learning algorithms using a customer retail dataset. It includes data preprocessing, visualization, model training, evaluation, and comparison of model performance.

The project is implemented using **Python**, **Pandas**, **Matplotlib**, and **Scikit-learn**.

---

## 🎯 Project Objective

The objective of this project is to:

- Load and preprocess a customer retail dataset.
- Handle missing values.
- Encode categorical data using LabelEncoder.
- Visualize customer retail data.
- Train multiple Machine Learning models.
- Evaluate model performance using Accuracy Score and Confusion Matrix.
- Compare the performance of different classification algorithms.

---

## 📂 Dataset

The dataset contains customer retail transaction information.

### Features Used

- Quantity
- UnitPrice
- Country

### Target Variable

- Country (Encoded using LabelEncoder)

> **Note:** The dataset is not included in this repository because it exceeds GitHub's file size limit. Download or place the dataset in the project folder before running the code.

Expected dataset filename:

```
customer_retail csv file.csv
```

---

## 🛠 Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn

---

## 📚 Python Libraries

- pandas
- matplotlib
- scikit-learn

Install the required libraries using:

```bash
pip install pandas matplotlib scikit-learn
```

---

## ⚙ Project Workflow

### 1. Load Dataset

- Read the customer retail dataset using Pandas.

### 2. Data Preprocessing

- Remove missing values.
- Select required columns.
- Encode the Country column using LabelEncoder.

### 3. Data Visualization

Generate a scatter plot showing the relationship between:

- Quantity
- UnitPrice

### 4. Train-Test Split

Split the dataset into:

- 80% Training Data
- 20% Testing Data

### 5. Machine Learning Models

The following models are implemented:

- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

### 6. Model Evaluation

Each model is evaluated using:

- Accuracy Score
- Confusion Matrix

### 7. Model Comparison

The performance of all models is compared using a bar chart.

---

## 📊 Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 88.98% |
| Decision Tree Classifier | 89.03% |
| K-Nearest Neighbors | 88.52% |

**Best Performing Model:** Decision Tree Classifier

---

## 📈 Visualizations

The project includes the following visualizations:

- Scatter Plot (Quantity vs UnitPrice)
- Model Accuracy Comparison Bar Chart

---

## 📁 Project Structure

```
TASK-ML/
│
├── task.py
├── README.md
├── customer_retail csv file.csv (Not Included)
```

---

## ▶ How to Run

### Step 1

Clone the repository.

```bash
git clone https://github.com/your-username/TASK-ML.git
```

### Step 2

Move into the project directory.

```bash
cd TASK-ML
```

### Step 3

Install dependencies.

```bash
pip install pandas matplotlib scikit-learn
```

### Step 4

Place the dataset file inside the project folder.

Expected filename:

```
customer_retail csv file.csv
```

### Step 5

Run the project.

```bash
python task.py
```

---

## 📌 Output

The program generates:

- Cleaned dataset
- Scatter Plot
- Logistic Regression Accuracy
- Decision Tree Accuracy
- KNN Accuracy
- Confusion Matrix for each model
- Model Accuracy Comparison Graph

<img width="987" height="702" alt="Image" src="https://github.com/user-attachments/assets/8e6a9046-9629-4c2b-9c52-1d54438530d1" />

<img width="987" height="635" alt="Image" src="https://github.com/user-attachments/assets/d29608d3-53ab-43c7-ac51-4e936ab6f6ef" />

<img width="492" height="590" alt="Image" src="https://github.com/user-attachments/assets/884e4798-5310-43de-adc9-156ca7827f9d" />

  ## sample output
  Accuracy: 0.8897573925226753
Confusion Matrix:
[[    0     0     0 ...     0   229     0]
 [    0     0     0 ...     0    78     0]
 [    0     0     0 ...     0     5     0]
 ...
 [    0     0     0 ...     0    13     0]
 [    0     0     0 ...     0 72396     0]
 [    0     0     0 ...     0    43     0]]

Decision Tree
Accuracy: 0.8903473195192095
[[   13     0     0 ...     0   197     0]
 [    0     0     0 ...     0    75     0]
 [    0     0     0 ...     0     5     0]
 ...
 [    0     0     0 ...     0    13     0]
 [   21     0     0 ...     1 72222     0]
 [    0     0     0 ...     0    43     0]]

KNN
Accuracy: 0.8851977484452965
[[   18     0     0 ...     0   180     0]
 [    0     1     0 ...     0    75     0]
 [    0     0     0 ...     0     5     0]
 ...
 [    0     0     0 ...     0    12     0]
 [   36     1     0 ...     0 71772     0]
 [    0     0     0 ...     0    43     0]]



---

## 🎓 Learning Outcomes

Through this project, the following concepts were learned:

- Data preprocessing
- Handling missing values
- Label Encoding
- Data visualization using Matplotlib
- Train-Test Split
- Supervised Machine Learning
- Logistic Regression
- Decision Tree Classification
- K-Nearest Neighbors (KNN)
- Accuracy Score
- Confusion Matrix
- Model comparison techniques

---

## 🚀 Future Improvements

Possible improvements include:

- Feature Scaling using StandardScaler
- Hyperparameter tuning
- Cross-validation
- Precision, Recall, and F1-Score evaluation
- Additional Machine Learning models such as Random Forest and Support Vector Machine (SVM)

---

## 👩‍💻 Author

**Lavanya Datti**

Machine Learning Project using Python and Scikit-learn.
