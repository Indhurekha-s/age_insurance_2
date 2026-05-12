# age_insurance_
# Insurance Purchase Prediction using Logistic Regression

## 📌 Project Description
This project uses the **Logistic Regression** algorithm to predict whether a person will purchase insurance based on their age.  
The model is trained using a small dataset containing customer ages and insurance purchase status.

The project demonstrates:
- Data loading using Pandas
- Train-Test splitting
- Logistic Regression model training
- Prediction and probability calculation
- Sigmoid function implementation
- Data visualization using Matplotlib

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset Information
The dataset contains:
- **age** → Age of the customer
- **bought_insurance** → Insurance purchase status  
  - `0` = Not Purchased  
  - `1` = Purchased

---

## ⚙️ Project Workflow

### 1. Import Required Libraries
Libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn are imported.

### 2. Load Dataset
The insurance dataset is loaded using Pandas.

### 3. Split Dataset
The dataset is divided into:
- Training Data (80%)
- Testing Data (20%)

### 4. Train Logistic Regression Model
The Logistic Regression model is trained using customer age data.

### 5. Make Predictions
The trained model predicts whether a customer will buy insurance.

### 6. Calculate Accuracy
The accuracy score is calculated using test data.

### 7. Implement Sigmoid Function
A manual sigmoid function is created to understand Logistic Regression mathematically.

### 8. Visualize Results
Graphs are plotted to visualize:
- Data points
- Logistic Regression curve
- Probability distribution

---

## 📊 Output
The model predicts:
- Whether a customer will buy insurance
- Probability of insurance purchase

Example:
- Age = 35 → Lower probability
- Age = 43 → Higher probability

---

## 📈 Logistic Regression Formula

z = mx + c

Sigmoid Function:

σ(x) = 1 / (1 + e^-x)

---

## ▶️ How to Run the Project

1. Install required libraries:
  ```bash
pip install pandas numpy matplotlib scikit-learn
```
2. Open the notebook in Jupyter Notebook or VS Code.
3. Run all cells sequentially.
4. 
## ✅ Conclusion

This project demonstrates how Logistic Regression can be used to predict insurance purchases based on age. It helps in understanding binary classification, sigmoid function, prediction, and model accuracy in machine learning.
