# HR DATA ANALYTICS DASHBOARD USING POWER BI
## Objective

The objective of this project is to identify and help an organization to improve employee performance and employee retention and also reduce attrition by creating a HR Analytics Dashboard.
This dashboard provides insights of the attrition of an organization which helps the HR team for their further analysis.

Interactive dashboard : https://app.powerbi.com/groups/me/reports/9276cf44-8a6f-4e62-9fbf-53c737f5a71f/b5dfa5cfee917233e6af?experience=power-bi
## Steps Followed:
**1. Data Gathering:**
- Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.
          
**2. Data cleaning:**
  - Cleaning is done by removing empty column, removing duplicates, errors etc.
  - Replacing values in column with proper values and naming.
  - Detecting data type of every column, using the auto detect data type function in Power query editor.
          
**3. Data processing:**
  - In the Power Query editor, creating new column called "AttritionCount" by using conditional column feature in add column which is created on the basis of certain condition like (IF attrition = 'Yes' then 1, Else 0).
  - This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.
          
**4. Data analysis:**
  - Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.
  - These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.

## Project Learning:
1. Identified key factors to reduce attrition
2. Improved the hiring process
3. Improved employee experience
4. Made workforce more productive 
5. Gained employee trust
### DASHBOARD:
![Dashboard](https://github.com/Pradeepa2003/HR-Data-Analytics-using-Power-Bi/assets/84965926/c1362229-6ec1-4f51-a086-cbce584297e1)
