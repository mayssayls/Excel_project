# My Excel Data Analytics Project
## Salary Dashboard    
This project is from the 'Excel for Data Analytics' course by Luke Barousse. It visualises the median salaries for jobs in the data science field. The point is to provide job seekers with insights on how differents data science roles are compensated across different countries and with different schedule types.  
The link of the file is [here](Project1_Salary_Dashboard.xlsx).

![capture_salary_dashboard](https://github.com/user-attachments/assets/105a45a0-73c9-41bd-9668-fa4adb1b4121)  
### Excel Skills used
- Formulas and functions
- Data Validation
- Charts
### Data Jobs Dataset 
The dataset in this project contains real-world data information from 2023 of the data science job including details about:
- Job titles
- Countries
- Locations
- Yearly Salaries
- Schedule Types
### Dashboard Build
#### Formulas and Functions  
##### Median salaries by job title  
![capture function](https://github.com/user-attachments/assets/168e1cbf-f646-412a-b6ab-a636a0b2e218)   

This formula reflects:  
-  Multi criteria filtering : where we filter Yearly salaries based on specific job title, country, and schedule type while excluding blank salaries.
-  It applies the MEDIAN function with a conditional IF to analyze the array by presenting the conditions related to calculating the median salary.
-  The returning value of this formula is to populate the table below, representing the median salary by job title, country, and schedule type.
  
  ![capture result function](https://github.com/user-attachments/assets/fa61c193-b233-46b0-9c9f-0a2ea8e79591)
  ### Charts
  #### Clustered bar chart
  ![capture bar](https://github.com/user-attachments/assets/8d3852f2-ac5d-474f-bb0c-72c3e8b7dd24)  

  - This bar chart utilizes the previous table of median salaries to visualize the  median salaries of different jobs in the data science field.
  - Horizontal bars are suitable for ranking comparisons.
  - Only two colors to distinguish between the selected job title and the others jobs.
  - Data orgnizations: The jobs are sorted in a descending order for an enhanced clarity and comparison.
  - Provides an identification on salary trends as it shows that senior roles and engineers are generally higher paid than analyst roles.
 #### Map chart
![map chart](https://github.com/user-attachments/assets/02d88230-87d2-47d7-967e-735c1c8965eb)
- Color coded map that shows salary distribution by country, with darker color representing higher slaries , light colors representing low ones.
- Plotted data when selecting different countries on the map.
- Gives highlights on low\high salary countries.

  ### Data Validation
![valid](https://github.com/user-attachments/assets/0f2a0c02-7790-4b50-b015-b928d08191c5)  
Filtered Lists are used for Job titles , country , and schedule type job.
 - Preventing invalid entries by only allowing selction from the predefined list.
 - Fcailitating data entry
 -  Making the dashboard more usable by enhancing and cleaning its overall structure.

 
## Salary Analysis

