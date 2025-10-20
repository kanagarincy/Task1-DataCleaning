 ask 1 – Data Cleaning and Preprocessing

**Internship:** Data Analyst Intern  
**Organization:** Elevate Labs  
**Dataset Used:** Mall Customer Segmentation Data (400 records)

---

## Steps Performed
1. Loaded dataset using Pandas.
2. Checked and removed missing values.
3. Removed 1 duplicate record.
4. Renamed columns to lowercase and underscore format.
5. Standardized categorical column (`Gender`).
6. Converted `Age` column to integer type.
7. Added new column `Age_Group` for segmentation.

---

## Final Outputs
- **Cleaned dataset:** cleaned_mall_customers.csv  
- **Rows after cleaning:** 399  
- **Columns:** 6 (customerid, gender, age, annual_income_(usd), spending_score_(1-100), age_group)

---

## Tools Used
- Python 3  
- Pandas Library

---

## Output Screenshot
Original Data:
   CustomerID  Gender   Age  Annual Income (USD)  Spending Score (1-100)
0           1    Male  41.0               133874                       1
1           2  Female  69.0                40289                      63
2           3    Male  28.0                30485                      54
3           4    Male  66.0                59482                      55
4           5    Male  25.0               101188                      40

Missing values before cleaning:
CustomerID                0
Gender                    1
Age                       1
Annual Income (USD)       0
Spending Score (1-100)    0
dtype: int64

Removed 1 duplicate row

Renamed Columns: ['customerid', 'gender', 'age', 'annual_income_(usd)', 'spending_score_(1-100)']

Cleaned Data Sample:
   customerid  gender  age  annual_income_(usd)  spending_score_(1-100)  \
0           1    Male   41               133874                       1   
1           2  Female   69                40289                      63   
2           3    Male   28                30485                      54   
3           4    Male   66                59482                      55   
4           5    Male   25               101188                      40   

  age_group  
0     41-50  
1       50+  
2     21-30  
3       50+  
4     21-30  

✅ Cleaned dataset saved successfully as 'cleaned_mall_customers.csv'

✅ Cleaned dataset saved successfully and is ready for analysis.
