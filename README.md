# ☕ SQL Data Cleaning Project – Coffee Store Sales

## 📌 Project Overview  
This project focuses on **data cleaning in SQL**. I worked with a very dirty cafe store sales dataset and transformed it into a **ready-to-analyze dataset** using MySQL.  

The process included:  
- Handling missing values  
- Standardizing categorical variables  
- Fixing inconsistent entries  
- Converting data types  
- Recalculating numerical fields (quantity, price per unit, total spent)  
- Ensuring data integrity and consistency  

---

## 🗂 Dataset  
The raw dataset (`orders`) contained **dirty and inconsistent records**. A cleaned version (`dorders`) was created for analysis.  

### Original Issues Identified  
- Empty strings (`""`), `"ERROR"`, and `"UNKNOWN"` values  
- Wrong data formats in `transaction_date`  
- Missing and incorrect values in `quantity`, `price_per_unit`, and `total_spent`  
- Inconsistent product pricing  
