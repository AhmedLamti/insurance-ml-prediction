# Insurance Prediction - Machine Learning Project

## 📌 Project Overview
This project focuses on building a **Machine Learning model** to predict insurance-related outcomes using structured data.  
It involves **data preprocessing, exploratory data analysis (EDA), feature engineering, and model training** with evaluation metrics.  

The project was developed in Python using **Scikit-learn, Pandas, NumPy, Matplotlib, and Seaborn**.

---

## 📂 Dataset
- **train_Insurance.csv** → Training dataset  
- **test_Insurance.csv** → Test dataset  

### Key preprocessing steps:
- Removal of irrelevant columns (`Customer Id`)  
- Handling of missing values and duplicates  
- Data cleaning and transformation (e.g., converting categorical values, replacing special string values like `without` or `>=10`)  
- Outlier treatment using **log transformation** and **IQR-based capping**  
- Feature scaling (RobustScaler / MinMaxScaler when required)  

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features (histograms, KDE plots)  
- Boxplots to detect and treat outliers  
- Correlation analysis between features  
- Impact of categorical variables on the target  

---

## ⚙️ Machine Learning Models
Implemented models include:
- **Decision Tree Classifier**
- **Random Forest Classifier**

### Model evaluation metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix**

Cross-validation techniques were also applied for better generalization.

---

## 📊 Results
- Decision Trees provided an interpretable baseline model.  
- Random Forest improved performance with better generalization.  
- Metrics (Accuracy, Precision, Recall, F1-score) were compared to select the final model.  

---

## 🛠️ Tech Stack
- **Language**: Python 3  
- **Libraries**:  
  - `numpy`, `pandas` → data manipulation  
  - `matplotlib`, `seaborn` → visualization  
  - `scikit-learn` → preprocessing, modeling, evaluation  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/insurance-ml.git
   cd insurance-ml
