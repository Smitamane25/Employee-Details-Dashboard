# Employee-Details-Dashboard

### Dashboard Link : https://lookerstudio.google.com/s/sMW1zWazqis

## Problem Statement

This dashboard helps the company to understand their employees better. It helps the company to know detailed information about employees within an organization.Through different visualizations, they get to know number of employees across the different departments,number of employees as per job title,annual salary,location.This dashboard provides a comprehensive view of employee profiles and related information for decision-making and HR management.

Since, exit rate (almost 10.30 %) of employees are less than working number of employees, thus the employees are satisfied with the company. 




### Steps followed 

- Step 1 : Import data into Looker Studio, dataset is a google sheet file and give it a descriptive name.
- Step 2 :Click on "Text" to give title to dashboard
- Step 3 :Scorecard visuals(KPI) were added to the canvas, such as total employees, working employees, number of employees got bonus,average salary of employees,avg age of employees and exit rate.
         Exit rate KPI was created using calculated field.


  Following expression was written to calculate Exit rate,
  ![Screenshot 2024-06-27 160717](https://github.com/Smitamane25/Employee-Details-Dashboard/assets/171058471/4c2cc396-5adc-4eb2-8847-01b6f3ae9371)
        
        Exit Rate = COUNT(Exit Date)/COUNT(Employee ID)

- Step 4 :  Visual filters (Control) were added for four fields named "Date", "Country", "Department" & "Gender".
![Screenshot 2024-06-27 173934](https://github.com/Smitamane25/Smitamane25/assets/171058471/c557102b-2cdf-4034-8550-b12a021affc4)
- Step 5 : Add table with heatmap to show top 10 paid employee name by salary. For top 10 employees add no of rows as 10 and then sort it in descending order by annual salary.
![Screenshot 2024-06-27 171034](https://github.com/Smitamane25/Smitamane25/assets/171058471/36eacb83-c15d-4fdb-b762-649007171c7d)

- Step 6 : Add bar chart to show no. of employess under each job role.
![Screenshot 2024-06-28 161014](https://github.com/Smitamane25/Smitamane25/assets/171058471/cd5da1ea-069f-4469-b181-3f43143e24dd)
- Step 7 :  Add time series chart to show hiring data on yearly basis.Change the data type of hire date as year to show yearly basis data.
![Screenshot 2024-06-28 161027](https://github.com/Smitamane25/Smitamane25/assets/171058471/55ff45e6-9d73-4414-b170-ee99f9a13be3)
- Step 8 : Add bubble map chart to show no of employees in different cities of different countries like US, China, Brazil.
![Screenshot 2024-06-28 161047](https://github.com/Smitamane25/Smitamane25/assets/171058471/72c61a6a-dcb2-4587-a852-8876e5edd45c)

- Step 9 : Add tree map to show employee strength in each business unit.
![Screenshot 2024-06-28 170436](https://github.com/Smitamane25/Smitamane25/assets/171058471/afac09cd-f7d0-4177-9c10-3f502b1fd130)
           
- Step 10 : Add pie chart to show no of employee in percentage in each deprtment.
![Screenshot 2024-06-28 161111](https://github.com/Smitamane25/Smitamane25/assets/171058471/986baab9-9b26-4db8-afc1-58f345ace4d9)
 
 - Step 11 : The report was then published to Power BI Service.
 
 # Report Snapshot (Looker Studio)

 
![Screenshot 2024-06-28 161211](https://github.com/Smitamane25/Smitamane25/assets/171058471/f0782d50-d0f1-42bd-8a50-830800799dc5)

# Insights

A single page report was created on looker studio & it was then shared with people.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Employees = 1000

      a) Number of Employees (Male) = 485 
      b) Number of Employees (Female) = 515
      c) Number of working employees = 897
      d) Number of employees exited from company = 103(10.30%)
thus, Exit rate of employees is less than no of working employees.
           
  
  ### [2] Number of Employees by Job Title
  
      a) Manager = 109
      b) Vice President = 108
      c) Sr. Manager = 92
      d) Director = 90
Above job title have maximum number of employee.

 ### [3] Hiring of Employees
 
 The hiring capacity of employees increasing yearly from 1993 to 2022,thus the highest hiring was in year 2018 and 2022.


 ### [4] Location

      a) United States = 634
      b) China = 227
      c) Brazil = 139
thus, maximum no of employees are belongs to United States .

### [5] Number of Employees by Business Unit
  
      a) Speciality Products = 266
      b) Research and Development = 254
      c) Corporate = 254
      d) Manufacturing = 226

### [6] Number of Employees by Department
  
      a) IT = 277
      b) Sales = 150
      c) Engineering = 141
      d) Accounting = 115
      e) Marketing = 110
      f) Human Resources = 109
      g) Finance = 98
thus, IT department have maximum number of employee.
