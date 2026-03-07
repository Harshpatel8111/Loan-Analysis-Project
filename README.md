# Loan-Analysis-Project

### Dashboard Link : https://drive.google.com/file/d/1gJItX0eK_9haWaBlsOTZykY74l8T2D_0/view?usp=sharing

### Problem Statement 
This Dashboard helps finance team and lending to understand the loan performance over the period and default risk with various borrower segment. It will help to know about the high risk profile, factor which plays important role in loan defaults as a result they will improve the lending decisions.

###  Dataset Overview
Dataset Name: Loan_Default  
Total Records: 255,347  
Source Systems:  
SQL Server  
Power BI Dataflows  
Excel (validation)  

#### Key Attributes

Financial: Income, Loan Amount, Interest Rate, DTI Ratio  
Demographic: Age, Education, Marital Status  
Employment: Employment Type, Months Employed  
Risk: Credit Score, Default Indicator  
Loan Details: Loan Purpose, Loan Term, Loan Date

### Steps
####Data Ingestion & Setup  
Step 1: Created a dedicated Power BI workspace named Data Flow  
Step 2: Installed and configured On-Premises Data Gateway  
Step 3: Created SQL Server database LOAN  
Step 4: Built Power BI Dataflow (Gen1) to ingest data from SQL Server  
Step 5: Connected Power BI Desktop to Dataflow and loaded dataset  

####Data Preparation & Profiling  
Step 6: Reviewed column statistics to identify:  
Null values  
Data type mismatches  
Outliers  
Step 7: Validated data types for financial and demographic fields  
Step 8: Checked data quality using:  
Power BI column profiling  
Excel Pivot Tables (cross-validation)  

#### Data Validation and Reporting  
Report 1 -  Loan Default and Overview  
<img width="1431" height="772" alt="image" src="https://github.com/user-attachments/assets/ad390f86-841f-47b7-81d5-262c6f00ab3d" />
##### Loan Amount By Purpose
Key Insight  
Home Loans contribute the highest total loan amount.  
Business Decision  
Introduce stricter risk assessment and monitoring for homeloans to reduce the risk as homeloans is the top factor of lending loan. 
##### Average Income by Employment Type  





