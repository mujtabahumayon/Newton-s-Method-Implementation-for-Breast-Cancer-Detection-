# 🧠 Newton’s Method - Machine Learning Mini Project

![Project Badge](https://img.shields.io/badge/Status-Completed-green)   
![ML Badge](https://img.shields.io/badge/Machine%20Learning-Python-orange)

## 📌 Project Overview

This project implements **Newton’s Method** to optimize a logistic regression model for the **Breast Cancer Wisconsin dataset**. The accuracy of the Newton's Method model is then compared with **Scikit-learn's Logistic Regression** model.

## 📂 Dataset

- Dataset: [Breast Cancer Wisconsin (Diagnostic)](http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- Files used: `wdbc.data`, `wdbc.names`

## 🛠 Technologies & Tools

- **Python** 🐍
- **Pandas** 📊
- **NumPy** 🔢
- **Matplotlib** 📈
- **Scikit-learn** 🤖

## ⚙️ Project Workflow

1. **Load Dataset** 📥  
   - Import the `wdbc.data` file using `pandas.read_csv()`.  
   
2. **Data Preprocessing** 🔧  
   - Assign appropriate column names.  
   - Convert `M` (malignant) to `1` and `B` (benign) to `0` in the `Diagnosis` column.  
   - Handle missing values if present.

3. **Train-Test Split** 🏋️‍♂️  
   - Split the dataset into **80% training** and **20% testing**.

4. **Newton's Method Implementation** 🧮  
   - Define the **sigmoid function**.  
   - Apply **Newton’s Method for optimization**.  
   - Compute the **cross-entropy loss function**.  
   - Check for **convergence**.

5. **Evaluate the Model** 🎯  
   - Set parameters for iterations.  
   - Compute the **accuracy of Newton’s Method**.

6. **Compare with Logistic Regression (Sklearn)** ⚖️  
   - Implement logistic regression using **Scikit-learn**.  
   - Compute the accuracy.  
   - Compare results.  

## 📊 Results

| Model               | Accuracy (%) |
|---------------------|-------------|
| **Newton’s Method** | **93.20%**   |
| **Logistic Regression (Sklearn)** | **96.49%** |

## 📌 Conclusion

- **Newton’s Method** performs well but is slightly less accurate than **Scikit-learn’s Logistic Regression**.
- **Advantages** of Newton’s Method:
  - Faster convergence for well-conditioned problems.
  - Avoids manually selecting step size.
- **Disadvantages**:
  - Requires **second-order derivatives**, which may be computationally expensive.

## 📖 References

- [Scikit-Learn Logistic Regression Docs](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)  
- [CMU Lecture on Newton's Method](https://www.cs.cmu.edu/~mgormley/courses/10701-f16/slides/lecture5.pdf)  
- [GeeksforGeeks - Newton-Raphson Method](https://www.geeksforgeeks.org/program-for-newton-raphson-method/)

---

🚀 **Developed by:** [Mujtaba Humayon](https://github.com/yourgithub)  
📌 **License:** MIT  
