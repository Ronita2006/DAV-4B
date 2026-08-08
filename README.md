# Z-Test Hypothesis Testing on Diabetes Dataset

This project performs a **one-sample Z-test** on the UCI Diabetes dataset to test whether the mean Glucose level significantly differs from a specified value (100).

## 📌 Features
- Load dataset (`uci_diabetes.csv`) using **Pandas**
- Perform Z-test on the `Glucose` column
- Calculate:
  - Z-statistic
  - P-value
- Interpret results at a 5% significance level:
  - Reject or fail to reject the null hypothesis

## 🚀 Usage
1. Place `uci_diabetes.csv` in the project directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
