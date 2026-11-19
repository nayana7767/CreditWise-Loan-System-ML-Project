# 💳 CreditWise – Loan Approval Prediction System

## 📌 Project Overview

CreditWise is a Machine Learning mini project that predicts whether a loan application will be approved or rejected based on applicant information.

The project focuses on understanding loan approval patterns through Exploratory Data Analysis (EDA), data preprocessing, feature engineering, and Machine Learning classification algorithms.

## 🎯 Objectives

- Analyze loan applicant data.
- Handle missing values and preprocess datasets.
- Explore relationships between applicant features and loan approval.
- Build and evaluate Machine Learning classification models.
- Compare model performance using accuracy and precision.

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine Learning algorithms and preprocessing
- **Jupyter Notebook** – Development environment

## 📂 Project Structure

```text
CreditWise-Loan-System-ML-Project/
│
├── Credit_Wise.ipynb
├── loan_approval_data.csv
└── README.md
```

## ⚙️ Project Workflow

### 1. Data Loading
- Imported the loan approval dataset using Pandas.
- Examined the dataset and its structure.

### 2. Data Preprocessing
- Handled missing numerical values using mean imputation.
- Handled missing categorical values using most frequent imputation.
- Removed the unnecessary Applicant_ID column.
- Applied Label Encoding and One-Hot Encoding to categorical features.

### 3. Exploratory Data Analysis (EDA)
- Analyzed loan approval distribution.
- Visualized credit scores based on loan approval status.
- Generated a correlation heatmap.
- Examined relationships between numerical features and loan approval.

### 4. Feature Scaling and Data Splitting
- Separated independent and dependent variables.
- Split the dataset into 80% training and 20% testing data.
- Applied StandardScaler for feature scaling.

### 5. Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## 📊 Model Performance

The models were evaluated using Accuracy and Precision.

| Algorithm | Accuracy | Precision |
|---|---:|---:|
| Logistic Regression | 86.5% | 78.33% |
| KNN (k=3) | 74.0% | 57.38% |
| Gaussian Naive Bayes | 86.5% | 80.36% |

**Observation:** Gaussian Naive Bayes achieved the highest precision, while Logistic Regression and Gaussian Naive Bayes achieved the same accuracy on the test dataset.

## 🚀 How to Run the Project

### Step 1: Clone the repository

```bash
git clone https://github.com/nayana7767/CreditWise-Loan-System-ML-Project.git
```

### Step 2: Navigate to the project directory

```bash
cd CreditWise-Loan-System-ML-Project
```

### Step 3: Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the notebook

Open `Credit_Wise.ipynb` and run the cells.

**Note:** Keep `loan_approval_data.csv` in the same directory as the notebook.

## 📈 Future Improvements

- Experiment with additional classification algorithms.
- Perform hyperparameter tuning.
- Improve model evaluation using confusion matrices, recall, and F1-score.
- Develop an interactive loan approval prediction interface.
- Deploy the trained model as a web application.

## 👩‍💻 Author

**Y Nayana**

GitHub: [nayana7767](https://github.com/nayana7767)

---

⭐ If you find this project interesting, feel free to explore the repository!
