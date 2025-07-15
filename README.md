# HR_analysis
## HR Insight and Analysis
This repository features a dynamic and comprehensive Power BI dashboard designed to empower Human Resources teams. It provides deep insights into employee activities, uncovers key workforce trends, and delivers actionable intelligence to support strategic decision-making and drive organizational growth.

---

Project Overview

- **Goal:** Build an interactive Human Resource dashboard to track employees who are not due for promotion, total employee by service year, total employee by job level, percentage of female and male workforce in the organization and employees who are due for promotion.
- **Tools Used:** Power BI for visualization.
- **Data Source:** Simulated employee dataset including:
- Age  
- Attrition  
- BusinessTravel  
- DailyRate  
- Employee_Num  
- Department  
- DistanceFromHome  
- Education  
- EducationField  
- EmployeeCount  
- EnvironmentSatisfaction  
- Gender  
- HourlyRate  
- JobInvolvement  
- JobLevel  
- JobRole  
- JobSatisfaction  
- MaritalStatus  
- MonthlyIncome  
- MonthlyRate  
- NumCompaniesWorked  
- Over18  
- OverTime  
- PercentSalaryHike  
- PerformanceRating  
- RelationshipSatisfaction  
- StandardHours  
- StockOptionLevel  
- TotalWorkingYears  
- TrainingTimesLastYear  
- WorkLifeBalance  
- YearsAtCompany  
- YearsInCurrentRole  
- YearsSinceLastPromotion  
- YearsWithCurrManager  
- **Audience:** HR managers, business analysts, and executives.

---

## Dashboard Highlights

The dashboard includes several key visualizations:

| Visualization | Description |
|---------------|-------------|
| Employees Due for Promotion (Card / KPI Metric) | Displays the total number of employees eligible for promotion based on time since last promotion. |
| Employees Not Due for Promotion (Card / KPI Metric) | Shows employees recently promoted or not yet meeting the promotion threshold. |
| Employees by Service Year (Bar Chart) | Groups employees based on years of service to identify tenure distribution across the organization. |
| Employees by Job Level (Column Chart) | Visualizes the distribution of employees across job levels, highlighting workforce composition. |
| Number of employee by Gender (Pie Chart) | Percentage of Male and Female workforce in the organization |

---

## Key Insights & Recommendations

### KPI Insight Summary

![image alt](https://github.com/wolethomas78/HR_analysis/blob/8a05e6d467b37d017d2d24f6c6c265209527ae42/NotDue_Promotion.png)

**Chart Referenced:**  
**Employees Not Due for Promotion (KPI Card)**

**Observation:**  
There are **870 employees** currently **not due for promotion** based on the promotion eligibility criteria.

**Interpretation:**  
A significant portion of the workforce has either been **recently promoted** or **does not yet meet** the threshold for promotion. This may indicate a **stable workforce** or potentially a **development lag** for newer or early-career employees.

**Recommendation:**  
Monitor this group's progression to ensure timely readiness for future promotions. Implement **career development plans** (e.g., training, mentorship, rotation programs) to prepare them for advancement. Ensure **clear communication** of promotion pathways and use supporting metrics (e.g., attrition risk) to anticipate engagement issues.

---
![image alt](https://github.com/wolethomas78/HR_analysis/blob/f9ed6b17c971d328682f066b1ec42fa313598a9e/promotion_due.png)  

**Chart Referenced:**  
**Employees Due for Promotion (KPI Card)**

**Observation:**  
There are **40 employees** who are **currently due for promotion** based on tenure and time since last promotion.

**Interpretation:**  
This group represents employees likely ready for **career advancement**, and delaying promotion may result in **reduced motivation or increased attrition risk**. It may also signal areas where internal mobility or leadership pipeline planning is needed.

**Recommendation:**  
Prioritize **performance evaluations** and consider this group for promotion or role enhancement. Incorporate them into **succession planning** and leadership development tracks. Ensure that promotion decisions are **equitable, data-driven**, and aligned with business needs.

---
![image alter](https://github.com/wolethomas78/HR_analysis/blob/bdcbe3c03d71004ecb94d893c007b6d364ac5f6e/empl_by_Serviceyear.png)

**Chart Referenced:**  
**Total Employees by Service Year (Bar Chart)**

**Observation:**  
- **127 employees** have **5 years** of service  
- **104 employees** have **1 year** of service  
- **80 employees** have **3 years** of service

**Interpretation:**  
The data shows a **healthy spread of employee tenure**, with a significant number of long-tenured staff (5 years) and a strong intake of newer employees (1 year). The group at 3 years suggests moderate retention in the mid-term, possibly approaching promotion or development milestones. This indicates that the organization has both **experience stability** and **recent growth** in hiring.

**Recommendation:**  
- Leverage the **5-year group** as a source of internal knowledge, mentors, or leadership candidates.
- Engage the **1-year employees** with onboarding support, career path planning, and retention initiatives to reduce early attrition.
- Monitor the **3-year cohort** for **promotion readiness** or potential career stagnation; they are likely to be at a **critical decision point** in their employment lifecycle.

---

![image alter](https://github.com/wolethomas78/HR_analysis/blob/600bdad8fd1254448d38e80f1153e69c242bd835/emplbyjoblevel.png)

**Chart Referenced:**  
**Total Employees by Job Level (Column Chart)**

**Observation:**  
- **Job Level 1:** 314 employees  
- **Job Level 2:** 361 employees  
- **Job Level 3:** 131 employees  
- **Job Level 4:** 66 employees  
- **Job Level 5:** 38 employees

**Interpretation:**  
The majority of employees are concentrated in **Job Levels 1 and 2** (entry and early-mid level roles), making up over 75% of the workforce. This reflects a **pyramid-shaped organizational structure**, with fewer employees in higher-level (senior/leadership) positions. The sharp drop from Level 3 upward may indicate **limited advancement opportunities** or a highly selective promotion process.

**Recommendation:**  
- Develop **career progression paths** for employees in Levels 1–2 to encourage upward mobility and long-term retention.
- Review whether the **promotion criteria** from Level 2 to 3 and above are transparent and accessible.
- For higher levels (4–5), invest in **leadership development programs** and **succession planning** to ensure readiness for critical roles.
- Consider workforce planning to ensure the right balance between **operational staff and strategic leadership capacity**.

---

![image alter](https://github.com/wolethomas78/HR_analysis/blob/627746b21f8460f989d1cf109e589cc76a4f398e/emplbygender.png)

**Chart Referenced:**  
**Gender Distribution (Pie Chart)**

**Observation:**  
- **Male:** 60.88%  
- **Female:** 39.12%

**Interpretation:**  
The organization has a **male-dominant workforce**, with males making up over **60%** of total employees. This could reflect **industry norms**, historical hiring trends, or a potential **gender imbalance** in certain roles or departments. The gap suggests room for improvement in **gender diversity and inclusion**.

**Recommendation:**  
- Evaluate **recruitment practices** to ensure they support diversity and attract more qualified female candidates.
- Review **gender representation by department and job level** to detect structural or pipeline issues.
- Promote **inclusive policies**, such as flexible work arrangements, mentoring programs for women, and unbiased performance reviews.
- Set **diversity goals** and regularly track progress to improve representation and equity.

---

---
![image alter](https://github.com/wolethomas78/HR_analysis/blob/1ae819cc758c3cc634c71a2aff93e166c2414171/hr_dashboard.png)
## Methodology
- Calculate total employees from Eployee_number.
- Built the dashboard in Power BI.
- 
---
## Contact Me

Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/oluwolefagbemi) or email at wolethomas78@gmail.com for questions or collaborations!

---
## Why This Project Matters

This dashboard demonstrates how data-driven insights can enhance workforce planning, employee development, and organizational efficiency. It showcases skills in HR analytics, KPI tracking, and visualization — all critical for driving informed decisions in talent management, succession planning, and employee retention strategies.



