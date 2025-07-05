
# Customer Churn Prediction (Telco Dataset)

This project focuses on predicting customer churn for a telecom company using Python and basic machine learning techniques. It guides through the end-to-end pipeline including data cleaning, exploratory analysis, model building, and evaluation.

## 📁 Dataset

We use a modified version of the [Telco Customer Churn dataset] file is provided.

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn (for visualization)  
- Scikit-learn (for ML modeling)  
- Google Colab  

## ✅ Steps Followed

### 1. Data Collection & Cleaning
- Loaded CSV data into a pandas DataFrame  
- Checked for missing values and duplicates  
- Removed or imputed missing values  
- Encoded categorical variables using `pd.get_dummies()`  

### 2. Feature Engineering
- Separated features (X) and target (y)  
- Converted 'Churn' column to binary (0 = No, 1 = Yes)  

### 3. Train-Test Split
- Split the data using `train_test_split()` from scikit-learn  
- 80% training and 20% test data  

### 4. Model Building
- Used Logistic Regression model (`LogisticRegression()`)  
- Trained the model using `.fit()`  

### 5. Model Evaluation
- Evaluated the model using accuracy score and classification report  
- Printed confusion matrix and performance metrics  

## 📊 Example Output

```
Accuracy: 0.81
Precision, Recall, F1-score by class shown using classification_report
```

## 📂 How to Run

1. Open the notebook using [Google Colab](https://colab.research.google.com/).  
2. Upload the `telco_customer_churn.csv` dataset using the Colab file upload interface.   (For this run only 1st cell and your'll see the upload bar to upload the file)
# 3. Run the notebook cells sequentially.

---

Made with ❤️ for learning......
