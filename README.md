# Predicting-Salary-Range-using-ML-Techniques
### Problem Statement: Predict the pay-range a given employee would belong to, based on the analysis of different attributes of other employees & their respective pay-range.

The dataset is sourced from http://openbook.sfgov.org, which is part of the Government of San Francisco city's initiative in providing open & easily accessible data related to performance & spending across different departments of San Francisco City government. Salary range is the range of pay established by employers to pay to employees performing a particular job or function. Salary range generally has a minimum pay rate, a maximum pay rate, and a series of mid-range opportunities for pay increases.

The salary range is determined by market pay rates, organization, department, union, type and domain of jobs, established through market pay studies, for people doing similar work in similar industries in the same region of the country. Pay rates and salary ranges are also set up by individual employers and recognize the level of education, knowledge, skill, and experience needed to perform each job. Its a database of the salary and benefits paid to City employees since fiscal year 2013.

This data is summarized and presented on the Employee Compensation report hosted at http://openbook.sfgov.org
The different attributes which are assumed to influence an employee's pay-range & compensation, and features against which data was collected are given below -
1. Year Type - Fiscal (July through June) or Calendar (January through December)
2. Year - An accounting period of 12 months. The City and County of San Francisco operates on a fiscal year that begins on July 1 and ends on June 30 the following year. The Fiscal Year ending June 30, 2012 is represented as FY 2011-2012.
3. Organization Group Code - Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.
4. Organization Group - Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.
5. Department Code - Departments are the primary organizational unit used by the City and County of San Francisco. Examples include Recreation and Parks, Public Works, and the Police Department.
6. Department - Departments are the primary organizational unit used by the City and County of San Francisco. Examples include Recreation and Parks, Public Works, and the Police Department.
7. Union Code - Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).
8. Union - Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).
9. Job Family Code - Job Family combines similar Jobs into meaningful groups.
10. Job Family - Job Family combines similar Jobs into meaningful groups.
11. Job Code - Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.
12. Job - Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.
13. Employee Identifier - Each distinct number in the “Employee Identifier” column represents one employee. These identifying numbers are not meaningful but rather are randomly assigned for the purpose of building this dataset. The column does not appear on the Employee Compensation report hosted on openbook.sfgov.org, but that report does show one row for each employee. Employee ID has been included here to allow users to reconstruct the original report. Note that each employee’s identifier will change each time this dataset is updated, so comparisons by employee across multiple versions of the dataset are not possible.
14. Overtime - Amounts paid to City employees working in excess of 40 hours per week.
15. Other Salaries - Various irregular payments made to City employees including premium pay, incentive pay, or other one-time payments.
16. Retirement - City contributions to employee retirement plans.
17. Health/Dental - City-paid premiums to health and dental insurance plans covering City employees. To protect confidentiality as legally required, pro-rated citywide averages are presented in lieu of employee-specific health and dental benefits.
18. Other Benefits - Mandatory benefits paid on behalf of employees, such as Social Security (FICA and Medicare) contributions, unemployment insurance premiums, and minor discretionary benefits not included in the above categories.
19. Total Benefits - The sum of all benefits paid to City employees.
20. Class - Class of Normal salaries paid to permanent or temporary City employees.

The target/label comprises of the 3 pay-range:
1. Low range salary
2. Mid range salary
3. High range salary

