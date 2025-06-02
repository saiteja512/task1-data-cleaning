# Task 1: Data Cleaning and Preprocessing

## 📁 Dataset
- Name: Mall Customers Dataset
- Source: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

## 🛠 Tools Used
- Microsoft Excel

## ✅ Cleaning Steps Performed
1. **Removed Duplicates**  
   - Checked and confirmed: 0 duplicate rows in the final dataset.

2. **Handled Missing Values**  
   - Verified using Excel filters: No missing values in any column.

3. **Standardized Column Headers**  
   - Renamed columns for clarity:  
     - `CustomerID` → `customer_id`  
     - `Annual Income (k$)` → `annual_income_k`  
     - `Spending Score (1-100)` → `spending_score`  
   - Removed spaces and used lowercase consistently.

4. **Standardized Text Values**  
   - Gender values were standardized to `Male` and `Female`.

5. **Checked & Fixed Data Types**  
   - Ensured `customer_id`, `age`, `annual_income_k`, and `spending_score` are integers.

## 🧾 Deliverables
- ✅ Cleaned Dataset: `Mall_Customers_cleaned.xlsx.csv`
- ✅ This README.md file

## 🔍 Notes
- No date fields were present, so no date format changes were necessary.
- No outliers or extreme values were treated, as this step was out of scope for basic cleaning.

---
