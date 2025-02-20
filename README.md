# IBM HR EMPLOYEE ATTRITION

## SUMMARY 
Employees don’t just leave a company; they leave for different reasons.

In this IBM HR Employee Attrition data analysis, I aimed to uncover the most probable causes of attrition within the company and explore if there are any correlations between attrition and the available variables.

Here’s what I found:

Out of 1,470 employees, 237 left the company, resulting in an attrition rate of 16.12%. While more males left compared to females, 
this could be due to their relative high representation in the company.  males aged 18-20, especially those with less than a year of stay in the company, 
were more likely to leave. the chances of them leaving increases when they are 
working with a particular manager and their satisfaction rating is one and also working as sales rep or HR.

Although no strong linear correlations were identified among the variables, Distance from Home showed a slight positive trend—indicating that, 
the more the distance of an employee from the company is, the higher the chances of the person leaving the company.

Key influencers reveal that employees with less than two Total Working Years, with monthly income less than 2,800 dollar, or low job satisfaction rating of 1 are two to three times more likely to leave.

These insights highlight that attrition is driven by a complex combination of factors, including the number of years spent in the company, compensation, satisfaction, and managerial relationships,
 rather than a single variable.




# Let’s break down the key elements and insights from each chart:

# PAGE ONE   (OVERVIEW)
![overview](https://github.com/user-attachments/assets/c6d28878-0ff9-420a-8ead-21a138b74f52)

📊 Top Section (KPIs):
Total Employees: 1,470
Employee Attrition: 237 employees left the company.
Active Employees: 1,233 still employed.
Attrition Rate: 16.12% (Calculated as Employee Attrition / Total Employees × 100).
These KPIs give an immediate understanding of the scale of attrition in the company.

📈 Detailed Visuals Breakdown:
1️⃣ Department with Most Attrition (Pie Chart):
Sales: 38.56% (highest attrition rate).
Human Resources: 35.59%.
Research & Development: 25.84

3️⃣ Age Distribution in the Company (Histogram):
Shows the age spread of employees.
The highest concentration is around 25-40 years.
💡 Insight: Attrition could be influenced by age groups, especially if certain age ranges show higher turnover.

4️⃣ Attrition by Most Number of Years Spent in Company (Bar Chart):
Attrition is highest among employees with 0-5 years in the company
Fewer employees leave after crossing the 10+ years mark.
💡 Insight: Newer employees are more likely to leave, hinting at possible onboarding or job-fit issues. the gen Z issues, lol

5️⃣ Attrition by Most Number of Years Spent in Company – Actual (Line Chart):
A line chart showing actual attrition over tenure.
There is a peak in attrition at the early years of employment and another sharp spike after 30+ years.
💡 Insight: Early-stage attrition may be due to job dissatisfaction, while late-career attrition could be due to retirement.




# PAGE TWO   (CORRELATION)
![correlation](https://github.com/user-attachments/assets/636ab785-4abc-4190-8d5d-381e9a04a68b)

📊 Scatter Plots (Attrition Rate by Different Factors):
1️⃣ Attrition Rate by Gender and Distance From Home:

Slight upward trend: As distance from home increases, so does the attrition rate.
Both male and female employees show this pattern, though females might exhibit slightly higher sensitivity.
💡 Insight: Longer commutes could be driving higher turnover.
2️⃣ Attrition Rate by Gender and Years with Current Manager:

Attrition tends to be higher when employees have spent fewer years with their current manager.
Over time, attrition decreases, indicating that stronger manager-employee relationships may improve retention.
💡 Insight: Manager-employee rapport is crucial in reducing attrition.
3️⃣ Attrition Rate by Gender and Total Working Years:

Employees with fewer total working years show a higher attrition rate.
Attrition drops as employees gain more experience, possibly due to better job stability.
💡 Insight: Less experienced employees might be more prone to leave due to job dissatisfaction or growth opportunities.
4️⃣ Attrition Rate by Gender and Environment Satisfaction:

Higher attrition is seen when environment satisfaction is low.
As satisfaction increases, attrition decreases.
💡 Insight: Workplace environment plays a key role in retaining employees.
5️⃣ Attrition Rate by Gender and Relationship Satisfaction:

Similar to environment satisfaction, higher relationship satisfaction (likely with peers and supervisors) correlates with lower attrition.
💡 Insight: Positive work relationships reduce the likelihood of employees leaving.
🗝 Key Influencers Panel (Top Factors Affecting Attrition):
This section identifies the strongest drivers behind attrition:

Total Working Years ≤ 2 → Increases attrition likelihood by 3.23x.
Years at Company ≤ 1 → Attrition is 2.70x more likely.
Monthly Income ≤ $2,800 → Employees are 2.60x more likely to leave.
Job Level ≤ 1 → Attrition likelihood increases by 2.60x.
Years With Current Manager ≤ 0 → 2.57x higher attrition risk.
Low Job Involvement (≤1) and Low Environment Satisfaction (≤1) also significantly contribute.
💡 Key Takeaway:

Newer employees, low-income earners, and those with poor workplace satisfaction are at a higher risk of leaving.
Managerial relationships and job involvement are pivotal in employee retention.


# PAGE THREE   (POSSIBLE CAUSES)
![possible causes](https://github.com/user-attachments/assets/aa65baac-f3dd-4731-b4b7-271cc86abf65)

1️⃣ Attrition Rate by Business Travel:

Travel_Frequently employees have the highest attrition rate compared to those who travel rarely or not at all.
💡 Insight: Frequent business travel may contribute to employee burnout and higher turnover.
2️⃣ Attrition Rate by Education Field:

Life Sciences and Medical fields show moderate attrition, while Technical Degree holders have lower rates.
The Total bar shows the combined attrition across all fields.
💡 Insight: Certain education backgrounds may align better with company roles, reducing turnover.
3️⃣ Attrition Rate by Job Role:

Sales Representatives have the highest attrition rate (100%), followed by Laboratory Technicians (23.94%) and Human Resources (23.08%).
Roles like Research Director and Manager show significantly lower attrition.
💡 Insight: High-pressure or quota-driven roles (e.g., sales) tend to have higher turnover.
4️⃣ Attrition Rate by Environment Satisfaction:

Employees with the lowest environment satisfaction (rating 1) show the highest attrition.
💡 Insight: A poor work environment directly impacts retention.
5️⃣ Attrition Rate by Relationship Satisfaction:

Unlike environment satisfaction, attrition remains fairly consistent across different satisfaction levels.
💡 Insight: Relationship satisfaction may not be a strong driver of attrition here.
6️⃣ Attrition Rate by Work-Life Balance:

Employees rating Work-Life Balance as 1 (poor) exhibit the highest attrition.
💡 Insight: Poor work-life balance is a significant factor in employee turnover.
7️⃣ Attrition Rate by Distance From Home:

The histogram shows that employees living farther from work tend to have slightly higher attrition rates, with peaks around the 15-25 distance range.
💡 Insight: Longer commutes could lead to dissatisfaction and attrition.
8️⃣ Attrition Rate by Job Involvement:

Low involvement (rating 1) employees have the highest attrition, while those with higher involvement show lower rates.
💡 Insight: Engaged employees are more likely to stay.
9️⃣ Attrition Rate by Years with Current Manager:

The treemap shows the distribution of attrition based on how long employees have been with their current manager.
High attrition is seen among employees with 0-2 years under a current manager, suggesting the importance of manager-employee relationships over time.
💡 Insight: Poor managerial relationships in the early stages may contribute to turnover.

📌 Overall Insights:
High attrition is linked to:
Frequent business travel
Sales roles
Low environment satisfaction
Poor work-life balance
Low job involvement
Short tenure with current managers
Understanding these patterns can help HR teams develop targeted strategies (e.g., improving work-life balance, supporting high-turnover roles, enhancing manager relationships) to reduce attrition.




