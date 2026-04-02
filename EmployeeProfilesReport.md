This data set contains various employee data such as name, ID, qualification etc. HR metrics were used to calculate headcount, average leave balance, average salary etc. Analysis was also conducted between salary and education qualification. Visual filters were used to see the highest and lowest earners amongst the employees in each job category. A HR dashboard was then created, and valuable insights gained regarding employees. 

Step 1: How many people are in each job? 
Formula: Headcount = COUNTROWS(EmployeeProfiles) 
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/347386bd-74e5-4ab5-80e7-a8e7cd0b9c57" />
Step 2: Gender break-down of the staff 
Created a pie chart and selected the Headcount and Gender fields. A slicer was added to observe the distribution of gender by job category
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/31218306-1d51-4994-a846-d3a6d418ef25" />
Step 3: Age spread of the staff 
Transformed data, by adding a new group to the age column, then grouping the ages into bins of 5 values. A slicer was added to observe the age distribution by gender.
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/8ab9e1aa-b362-4daa-9495-bb450bf9c637" />
Step 4: Which jobs pay more? ​
Formula: Average Salary = AVERAGE(EmployeeProfiles[Salary]) ​
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/2dd51146-0891-4b82-a25d-da2b9cad31b8" />
Step 5: Top earners in each job category 
Transformed the salary column by adding $ sign in the beginning of the values. Filtered the table visual by "Top N" to show the employees who are paid the most/least by job title.
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/994850c7-d655-4dd5-b665-357532d3a848" />
Step 6: Qualification vs. Salary 
a) Created a qualification column index.​ b) Linked the field Employee Qualification in "Employee Table" with the Qualification field in "Education
Qualification" table.​ c) Created the scatter plot. 
​<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/c2383bc0-c7cc-46c4-8f49-f4272e378591" />
Step 7: Staff growth trend over time 
a) calculated Cumulative headcount. b) Created line chart by separating the data by Date of Join and not Date hierarchy <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/330fb3f3-b8f6-44ec-a3de-59c086f8eff4" />
Step 8: Employee filter by starting letter ​
Transformed data by adding a column and extracting the first character of the name column. ​Added a table with employee details and conditional formating of a data bar. <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/daadcd81-a13a-484f-9f26-4634d9986f8d" />
Step 9: Leave balance analysis ​
Calculated average leave​: Average Leave Balance = AVERAGE(EmployeeProfiles[Leave Balance])​ Also measured people who have greater than a months leave balance: ​Leave Balance greater than 20 days = CALCULATE([Headcount], EmployeeProfiles[Leave Balance] >20) <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/b73dfea2-9a1d-442f-817a-456125297e42" />
Step 10: Created a dashboard based on the above findings:
![Untitled design](https://github.com/user-attachments/assets/ddba4193-a21f-476d-8271-e7f7075a2a4e)

Data Insights: 

📊 Workforce Composition

• Headcount: 161 employees — a mid-sized organization.

• Roles: The workforce is spread across diverse functions, with Packaging (22), Production (20), and Research Scientist (20) being the largest groups. This suggests a balance between operational, creative, and analytical roles.

• Gender: 45% male and 55% female.

💰 Compensation & Leave

• Average Salary: $54K - indicates a moderate pay scale, likely reflecting a mix of entry-level and specialized roles.

• Leave Balance: Average of 16.42 days, but 29 employees have more than 20 days. Pointing to a possibility of underutilized leave or longer tenure.

👥 Demographics

• Age Distribution: Most employees are between 20–40 years old, showing a relatively young workforce. Few are above 50, which could mean limited senior-level experience or a focus on early-career talent.

• Qualifications vs Salary: Salaries range from $20K–$90K, with higher qualifications (Master’s, Bachelor’s) generally clustering at the upper end. Diploma and High School graduates appear in lower salary ranges, which aligns with typical market trends.

📈 Growth & Trends

• Hiring: 20 new employees joined in 2023, bringing the total to ~160. Growth has been steady since 2018, suggesting consistent expansion rather than rapid scaling.

🔑 Key Deductions
• Balanced workforce: gender distribution and role diversity are healthy.

• Young talent pool: majority under 40, which may drive innovation but could lack deep senior expertise.

• Leave accumulation: some employees may not be taking enough time off, which can affect wellbeing.

• Steady growth: hiring is consistent, not explosive, pointing to sustainable expansion.

• Qualification-driven pay: clear link between education level and salary, which could influence recruitment and retention strategies.


Credit to the following creator: YT Chandoo  
