This dataset included key employee information such as age, job role, attrition, and job satisfaction levels. Leveraging this data, I applied a structured process to develop a dashboard that highlights workforce attrition patterns and overall attrition rates. The resulting visualization provides actionable insights into employee turnover and satisfaction trends.

Step 1: Transformed Data by creating column headings.
​
Step 2: Created a card with sum of employee count.

Step 3: Calculated Attrition by adding a conditional column. 

Step 4: Calculated Attrition Rate using DAX query measure - Attrition Rate = SUM('HR Data'[Attriiton Count])/SUM('HR Data'[Employee Count]

Step 5: Calculated Active Employees by calculating the difference between Total Employees and Attrition Count.

Step 6: Created a pie chart of Attrition by Department.

Step 7: Created a line chart to show the distribution of employees by age and gender.​
  - Rearranged the y axis by creating a conditional age distribution. ​
  - Sort column by sorting age and setting to ascending order.
    
Step 8: Created a matrix chart of Job Satisfaction by Job Role.

Step 9: Created a bar chart with the attrition count by educational field.

Step 10: Created 5 donut charts to display the percentage of attrition by age group and gender.
  - Filtered CF age_band by age based on the doghnut title.
  - Yellow is male 🟡, orange is female 🟠. 

Step 11: Created a card within the doghnut to show the attrition by age group

Step 12: Added a slicer by Education, in the main dashboard

Step 13: Added a filter to view results and not only highlight them when selected by formatting and editing interactions. 

​
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/14468f54-32b7-48ed-ac3f-1fcf0f815811" />

Summary of findings: 

📊 Workforce Overview

• Total Workforce: 1,470 employees, with 237 attritions (16.12% attrition rate).

• Active Employees: 1,233, showing a significant reduction in headcount.

• Average Age: 37, suggesting a mid-career workforce profile.

🔎 Attrition Insights

• By Department:

    ⁃ R&D has the highest attrition (56%), followed by Sales (39%).

    ⁃ HR attrition is relatively low (5%).

  → This indicates retention challenges in technical and sales functions, which are often critical to business performance.

• By Education Field:

    ⁃ Life Sciences and Medical backgrounds show the highest attrition counts.

    ⁃ Marketing and Technical degrees also contribute notably.

  → Suggests that specialized skill areas may be harder to retain.

• By Age & Gender:

    ⁃ Younger employees (under 25 and 25–34) show the highest attrition, especially females in the 25–34 group.

    ⁃ Older age groups have lower attrition, but gender differences are visible (e.g., males 35–44 leaving more than females).

  → Indicates generational and gender-specific retention challenges.

💡 Employee Engagement

• Job Satisfaction Ratings:

    ⁃ Sales Executives and Research Scientists have the largest populations, but satisfaction scores vary widely.

    ⁃ Roles like Laboratory Technicians and Manufacturing Directors show mixed satisfaction levels.

  → Suggests that job satisfaction is uneven across roles, potentially driving attrition in certain categories.

🧭 What This Dashboard Reveals

• High attrition rate (16%) is a red flag, above typical benchmarks (often 10–12%).

• Retention issues are concentrated in R&D and Sales, which are strategic functions.

• Younger employees are leaving more, pointing to onboarding, career development, or engagement gaps.

• Gender differences in attrition highlight possible cultural or support issues.

• Job satisfaction data provides clues about where interventions (training, career paths, leadership support) could reduce turnover.

Credit: YT Data Tutorials 
