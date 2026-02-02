# AI-ML Internship – Task 8  
## Decision Tree Classification – Bank Marketing Dataset

---

## 📌 Objective  
The objective of this task is to build a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on bank marketing data, and to interpret the decision-making rules of the model.

---

## 📂 Dataset  
**Bank Marketing Dataset**

- Contains customer demographic and campaign-related information
- Target variable:
  - `deposit`  
    - `yes` → Customer subscribed  
    - `no` → Customer did not subscribe  

---

## 🛠 Tools & Libraries Used  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔍 Steps Performed

### 1. Data Loading  
- Loaded the Bank Marketing dataset using CSV file
- Inspected dataset shape, columns, and data types

---

### 2. Data Cleaning  
- Removed extra spaces and standardized column names
- Replaced `unknown` values with missing values
- Removed rows containing missing data

---

### 3. Feature and Target Selection  
- Separated independent features (`X`) and target variable (`deposit`)
- Verified class distribution using value counts

---

### 4. Data Preprocessing  
- Identified categorical and numerical features
- Applied **One-Hot Encoding** to categorical variables
- Passed numerical variables without scaling (Decision Trees do not require scaling)

---

### 5. Train–Test Split  
- Split the dataset into training and testing sets (80% train, 20% test)
- Used stratified sampling to preserve class balance

---

### 6. Model Training  
- Trained a **Decision Tree Classifier**
- Limited tree depth using `max_depth` to prevent overfitting

---

### 7. Model Evaluation  
The model was evaluated using:
- Training Accuracy
- Testing Accuracy
- Classification Report (Precision, Recall, F1-score)

Train vs Test accuracy was compared to analyze overfitting.

---

### 8. Decision Tree Visualization  
- Visualized the trained Decision Tree using `plot_tree`
- Interpreted splits and decision paths

---

### 9. Key Decision Rules  
- Longer call duration significantly increases subscription probability
- Successful outcome in previous campaigns positively impacts subscription
- Effective contact frequency influences customer decisions

---

## 📦 Deliverables  
- ✔ Jupyter Notebook (.ipynb)  
- ✔ Decision Tree visualization  
- ✔ Model evaluation report  

---


---

## ✅ Conclusion  
This task strengthened understanding of Decision Trees, model interpretability, overfitting control, and practical evaluation of classification models in real-world datasets.

---


## 📁 Repository Structure
