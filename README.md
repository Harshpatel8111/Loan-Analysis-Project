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
Key Insight  
Fulltime Employees have highest average income compare to other types where as unemployeed has lowest average income.  
Business Decision  
Increase the number loan and offer better loan terms to full time employees.  
##### Average Loan by Age Group  
Adults and Middle aged borrowers take highest average loans.  
Business Decision  
Keep increasing the number of loans for Adults and middle aged age group while limit the number for senior citizen age group to decrease risk.  
##### Default Rate(%) By Year  
Key Insight  
Default rates were between 11.50 and 11.75 in 6 years starting from 2013.
Business Decision  
Maintain the default rate under 11.50 to increase the profit from last 6 year.  
##### Default by Employeement Type  
Key Insight  
Unemployeement has highest default rate accounting for 3.39 followed by parttime, self employeed, and fulltime(2.30).  
Business Decision  
Increase the number of borrowers who have full time job security to decrease overall default rate. Meanwhile implement strict terms for unemployeed borrowers to decrease risk.  








