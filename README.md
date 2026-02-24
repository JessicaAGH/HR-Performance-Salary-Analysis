# 📊HR Performance Salary Analysis
## 📌 Project Description
This project involves a comprehensive analysis of employee data across multiple departments within an organization for the years 2019 and 2020. The primary objective is to consolidate dispersed departmental data into a unified report, create a dynamic pivot table report for multi-dimensional analysis, and design a high-level dashboard to visualize key performance indicators (KPIs). The analysis covers salary distributions, employee performance scores, demographic details like age and experience, and academic backgrounds to provide actionable insights for management.

## 🎯 Project Goals
- Data Consolidation: Integrate employee data from individual departmental sheets (Finance, HR, IT, Marketing, Sales) into a single, comprehensive "All Dept" dataset.

- Metric Calculation: Create new calculated fields within the consolidated data, including employee age, years of experience, average performance (2019-2020), and performance delta (change from 2019 to 2020).

- Multi-Dimensional Analysis: Develop a "Pivot Table Report" sheet to enable quick and flexible analysis of key metrics like average performance, total salaries, employee counts, and salary ranges across different dimensions such as Site, Job Role, and Academic Level.

- Executive Dashboard: Design an interactive and visual "Dashboard" to present the most critical, high-level insights at a glance, such as average salary, average performance, and department names.

- Insight Generation: Identify trends, strengths, and areas for improvement within the workforce based on the analyzed data.

## 📂 Data Sources
The data for this project is sourced from the Report.xlsx file, which contains the following sheets:
- Finance: Employee data for the Finance department.  
- HR: Employee data for the Human Resources department.  
- IT: Employee data for the Information Technology department.  
- Marketing: Employee data for the Marketing department.  
- All Dept: A consolidated sheet compiling data from all departments. It also includes calculated columns for Years of Experience, Age, total Avg Performance, and Delta. (Note: The 'Sales' department data is also found within this consolidated sheet).

## 🛠 Tools & Technologies Used
Microsoft Excel: The sole platform used for this project.  
  - Data Cleaning & Transformation: To standardize and prepare the raw data.  
  - Formulas & Functions: To create calculated columns using DATEDIF, AVERAGE, and basic arithmetic.  
  - PivotTables: To build the "Pivot Table Report" for interactive data exploration and summarization.  
  - Charts & Visuals: To design the elements within the "Dashboard" (though the provided sheet shows placeholders for these visuals).  
  - Slicers & Timelines (Potential): While not visible in the static output, these are standard tools that would be used for dashboard interactivity.  

## 📊 Overview
The **Report.xlsx** file is structured as a complete business intelligence workflow. It starts with raw data in departmental sheets (**Finance, HR, IT, Marketing**). This data is then consolidated into the **All Dept sheet**, where key performance and demographic metrics are derived. The **Pivot Table Report** sheet acts as an analytical layer, summarizing the consolidated data from various angles. Finally, the **Dashboard** sheet serves as the presentation layer, designed to visually communicate the most important findings to stakeholders.


## 🔎 Key Insights
The data from the "Pivot Table Report" reveals several significant trends:

- Declining Performance Across the Board: There is a clear and concerning trend of decreasing average performance from 2019 to 2020. The Grand Total average performance dropped from 0.818 in 2019 to 0.712 in 2020, a negative change of -0.106. This decline is most pronounced in the Alexandria (الإسكندرية) site (-0.16).  

- Site-Specific Salary and Performance Dynamics:
    - Alexandria (الإسكندرية) has the highest total salary expenditure (614,994) and the most employees (46). However, it has the lowest average 2020 performance (0.658) and the largest performance drop.  
    - Cairo (القاهرة) and Tanta (طنطا) show relatively better average performance in 2020 (0.773 and 0.731, respectively) compared to Alexandria.  
    - Tanta has the lowest average salary (12,029) but a mid-range performance drop, potentially indicating better value for money.

- Job Role Performance Variances: Certain roles have shown resilience or improvement. IT Managers and HR Managers both saw performance increases in 2020, while roles like HR Specialist and Recruitment Specialist experienced significant declines. Sales Manager also saw a drastic drop from 0.89 to 0.52.

- Salary Distribution: There is a wide salary range across the company, from a minimum of 1,428 to a maximum of 35,000. Sales Representatives, while numerous, have a highly variable total salary sum, indicating a mix of junior and senior staff.

- Workforce Demographics: The workforce is experienced, with an average of 14.3 years of experience and an average age of 50.7 years. This suggests a mature team, which could be a strength in expertise but may also present future succession planning challenges.

## 💡 Recommendations/Solutions
Based on the insights, the following actions are recommended:

#### 1️⃣Investigate the Performance Decline (2020 vs. 2019): 
A task force should be formed to understand the root cause of the widespread performance drop, particularly in Alexandria. Possible factors could include changes in management, market conditions, employee morale issues, or flawed performance appraisal system in 2020.  
✦ Action: Conduct exit interviews, employee surveys, and review departmental goals for 2020.  

##### 2️⃣Targeted Support for Underperforming Roles: 
Focus on roles with the steepest performance declines, such as HR Specialists and Recruitment Specialists.  
✦ Action: Review their job descriptions, provide additional training, ensure they have the necessary resources, and check in with their direct managers.  

#### 3️⃣Leverage High Performers: 
Recognize and analyze the strategies of roles that maintained or improved performance (IT Manager, HR Manager).  
✦ Action: Have these managers share their best practices with other department heads in a knowledge-sharing session.  

#### 4️⃣Compensation and Structure Review: 
Analyze the wide salary ranges within job roles (e.g., Sales rep.) to ensure internal equity and fair compensation based on experience and performance.  
✦ Action: HR should conduct a compensation audit to ensure salaries align with market rates, experience levels, and performance grades.  

#### 5️⃣Succession Planning: 
Given the mature workforce (average age 51), the company should proactively develop a succession plan.  
✦ Action: Identify high-potential younger employees and create mentorship and development programs to prepare them for leadership roles in the future.  

## 🏁 Final Note
The **Report.xlsx** file serves as an excellent example of a self-contained analytical project in Excel. It effectively transforms raw data into actionable business intelligence. The key findings highlight a critical period of performance decline that warrants immediate attention. By acting on the insights and recommendations derived from this report, the organization can work to reverse negative trends, support its employees better, and build a more resilient and high-performing workforce. The next logical step would be to connect this dashboard to a live data source for real-time tracking.
