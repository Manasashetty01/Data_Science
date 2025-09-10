Data Science Job Salaries — Final Report

Project Title: Data Science Job Salaries Analysis

Author: Manasa Shetty

Introduction

The rapid growth of Data Science as a profession has resulted in diverse career paths, ranging from entry-level analysts to senior executives and specialized AI/ML engineers. Salaries in this field vary significantly depending on multiple factors such as experience level, employment type, company size, remote work opportunities, and geographic location.
This project uses the Data Science Job Salaries dataset to analyze these variations. The goal is to identify trends and derive meaningful insights about compensation in the industry. The analysis is performed using Python in a Jupyter Notebook environment.

Dataset Description

The dataset contains 607 records and 12 columns with details about job roles and salaries.

Key Features:

•	work_year – Year of the job posting

•	experience_level – Career level (Entry, Mid, Senior, Executive)

•	employment_type – Full-time, part-time, contract, freelance

•	job_title – Job designation

•	salary – Reported salary

•	salary_in_usd – Standardized salary in USD

•	employee_residence – Country of the employee

•	remote_ratio – Degree of remote work (0 = on-site, 50 = hybrid, 100 = fully remote)

•	company_location – Country of the company

•	company_size – Small (S), Medium (M), Large (L)

The dataset required minimal cleaning, mainly ensuring consistency in categorical values and handling missing entries.

**Exploratory Data Analysis (EDA)**

Salary Distribution

Mean salary $112,298

Median salary  $101,570

Minimum salary  $2,859

Maximum salary  $600,000
 <img width="1019" height="490" alt="image" src="https://github.com/user-attachments/assets/5095b707-9977-4a1e-b7c7-2502c70f055d" />

The salary distribution is right-skewed, with most salaries concentrated between $100K–$150K. A few extremely high salaries create a long tail, making the mean much higher than the median.

**Salaries by Experience Level**

**Experience Level	Median Salary (USD)**

Entry (EN)	68,500

Mid (MI)	85,000

Senior (SE)	140,000

Executive (EX)	187,500
<img width="1040" height="493" alt="image" src="https://github.com/user-attachments/assets/4f3579cd-53ae-4d78-a40a-71a1c03fda2a" />


Salaries increase steadily with experience, showing a clear upward trend from entry-level to executive roles.Executives earn nearly 3 times more than entry-level professionals. Outliers are present at each level, but higher experience consistently leads to higher median pay.

**Salaries by Employment Type**

**Employment Type	Median Salary (USD)**

Full-time (FT)	115,250

Contract (CT)	105,000

Freelance (FL)	40,000

Part-time (PT)	34,500

<img width="940" height="667" alt="image" src="https://github.com/user-attachments/assets/efdfe588-59d4-4900-9a25-9372d5e628ad" />

Full-time roles dominate and provide the highest consistent salaries. Freelance and part-time roles offer significantly lower pay.

 **Salaries by Company Size**
 
**Company Size	Median Salary (USD)**

Small (S)	80,000

Medium (M)	116,075

Large (L)	120,250
 <img width="1033" height="626" alt="image" src="https://github.com/user-attachments/assets/81296d17-b45c-4c66-96fe-07e2f65665e0" />

Larger companies generally offer higher compensation packages than smaller firms.

**Salaries by Remote Ratio**

**Remote Ratio	Median Salary (USD)**

0% (On-site)	102,100

50% (Hybrid)	76,760

100% (Remote)	123,000
 <img width="988" height="471" alt="image" src="https://github.com/user-attachments/assets/161392ad-9e1b-44ab-bedc-1ea7187a0911" />

Fully remote jobs provide higher median salaries compared to on-site or hybrid roles.

**Top 10 Paying Job Roles**
 <img width="1003" height="572" alt="image" src="https://github.com/user-attachments/assets/c52fb6ed-92db-4d9e-b824-1be8d58e0a35" />

The role of Data Analytics Lead commands the highest average salary among data science job titles, exceeding $400,000 USD. Entry-level and mid-tier roles like Data Specialist and Analytics Engineer have noticeably lower average salaries, highlighting a significant compensation gap based on seniority and specialization.

Insights & Key Findings

•	Experience level is the strongest determinant of salary growth.

•	Full-time employment dominates with stable and high pay.

•	Large companies generally offer better compensation packages.

•	Remote opportunities pay better than on-site or hybrid roles.

•	Specialized roles Data Analytics Lead, Principal Data Engineer, Financial Data Analyst  consistently rank among the highest paid.

Conclusion

The analysis confirms that Data Science is a lucrative field with wide-ranging opportunities. Salaries, however, vary significantly by experience, employment type, company size, remote ratio, and geography.

For professionals: gaining experience, specializing in advanced roles, and exploring remote opportunities can maximize earning potential.

For employers: offering competitive salaries and remote flexibility can help attract top talent globally.

