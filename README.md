# Dynamic-Company-Salary-Review-Analysis
> This Excel work on Company A review case study aims to analyze salary structure of their staffs and how much each staff receives base on the company salary plan. Key features are: Clean Dashboard to support business decision making.
Case Study by Morrison (Analyst).

## Project Overview
> This case study analyses Dynamic Company Salary structure for each staff with the company. 

> ## Data Content
### Rows: were 320 in Total.
 ### Columns: were 16 in Total.
Product details: Employee ID, Employee name, department, Grade level, Basic, Housing, Transport, leave, meal, utility and gross.

> ## Tool Used
> Microsoft Excel (Excel functions).
## Data Cleaning Actions
> Some data cleaning steps were applied to make the dataset proper for analysis without errors.

> ## Steps
### Name Column: cleaned using Proper & Trim (nesting), removing extra spacing in names.
### Helper columns: calculated columns and category columns were used in generating the Dashboard.
<img width="800" height="420" alt="image" src="https://github.com/user-attachments/assets/3c8c4f05-a7f8-4766-8c83-d73d3422e01d" />
<img width="546" height="280" alt="image" src="https://github.com/user-attachments/assets/036429e3-40b8-4024-9a46-46e833cf073f" />

 
 
> ## Key Business Questions Answered

1.	Analyze and determine the salary structure for each staff, determine the salary pay for different grade level?
Add a calculated column:
 =VLOOKUP($E9,'Simple Salary Structure'!$B$7:$I$16,Database!F2,0)
NOTE: The table array column 2 would be changed for each column to be calculated. 
NOTE: A more simplified process was used to generate the table without repeating the process over again. Formula: =VLOOKUP($E9,'Simple Salary Structure'!$B$7:$I$16,Database!F$7,0)

> ## Section Details
> ### Column Names:. Employee ID, Employee name, department, Grade level, Basic, Housing, Transport, leave, meal, utility and gross
> ### Excel formulas used: PROPER() TRIM() VLOOKUP() 

## Analytics Dashboard
 <img width="546" height="280" alt="image" src="https://github.com/user-attachments/assets/c149652d-3980-4cb2-913f-767f56175f6a" />


> ## Findings
> 1.	Salary structure for each grade level generated.
> 2.	Analyses of other stipend added to the salary structure generated.
> 3.	Gross pay for each staff stated.

## Conclusion
Using Excel to generate business ready insight from identifying, understanding and knowing the Salary structure for each staff in the company to enable clear decision making in the company.

