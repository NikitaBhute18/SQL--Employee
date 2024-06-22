# Employee Information

## Project Link-

https://drive.google.com/drive/u/1/folders/1_KJyZH6sAwDroPp4Efv7KZ1G5m4CfVDL


Certainly! Let's explain each SQL query in the form of a report, detailing what information each query retrieves and its significance for the employee information project.

### 1. Showing Employee Information
This query simply retrieves all columns from the `Employee_info` table, providing a comprehensive view of each employee's details such as `EmployeeID`, `Name`, `Education`, `City`, `Age`, `ExperienceInCurrentDomain`, `EverBenched`, `LeaveOrNot`, `PaymentTier`, etc. This information serves as the foundational dataset for further analysis and reporting.

### 2. Count of Employees by Education
This query calculates the number of employees grouped by their educational qualifications (`Education`). It helps in understanding the distribution of educational backgrounds among employees, which can be crucial for various HR and planning purposes.

### 3. Average Age and Experience by City
This query computes the average `Age` and average `ExperienceInCurrentDomain` for employees grouped by `City`. It provides insights into the demographic and experiential profiles across different cities, aiding in location-specific HR strategies and resource allocation.

### 4. Count of Employees Ever Benched and Left
This query counts employees who have been benched (`EverBenched = 'Yes'`) and have left the organization (`LeaveOrNot = 1`). It helps in understanding the turnover rate among employees who have faced benching, highlighting potential issues or trends related to job satisfaction and retention.

### 5. Distinct Payment Tiers
This query retrieves distinct values of `PaymentTier` from the `Employee_info` table. It identifies the different payment levels or categories within the organization, which is essential for analyzing salary structures and compensation policies.

### 6. Maximum Age and Minimum Experience
This query calculates the maximum `Age` and minimum `ExperienceInCurrentDomain` across all employees. It provides an overview of the oldest and least experienced employees in the dataset, which can be useful for workforce planning and identifying potential mentors or retirees.

### 7. Average Age by City and Gender
This query computes the average `Age` of employees grouped by both `City` and `Gender`. It offers insights into age demographics across different cities while also considering gender diversity, which is crucial for assessing inclusivity and demographic trends within the organization.

### 8. Employees with PHD Education
This query retrieves all columns for employees whose `Education` is 'PHD'. It provides a specific subset of highly educated employees, which can be analyzed further to understand their roles, contributions, and potential impact on organizational research or innovation.

### 9. Average Age by Education
This query calculates the average `Age` of employees grouped by `Education`. It helps in understanding age profiles across different educational backgrounds, which can influence training programs, career development strategies, and recruitment efforts.

### 10. Count of Employees by Gender
This query counts employees grouped by `Gender`. It provides a gender distribution overview within the organization, which is essential for diversity reporting, gender-specific HR policies, and analyzing gender-related trends in various aspects of employment.

### 11. Employees in Payment Tier 3 with Experience > 3 Years
This query retrieves all columns for employees in `PaymentTier = 3` who have `ExperienceInCurrentDomain` greater than 3 years. It identifies a specific subset of mid-tier employees with significant domain experience, aiding in targeted retention strategies and career progression analysis.

### 12. Average Age by Benching Status
This query calculates the average `Age` of employees grouped by `EverBenched` status (`Yes` or `No`). It helps in understanding age-related differences between employees who have and haven't been benched, which can influence workforce management and employee support initiatives.

### 13. Maximum Experience by City
This query retrieves the maximum `ExperienceInCurrentDomain` for employees grouped by `City`. It identifies cities where employees have the most domain experience, which can be indicative of regional expertise and potential hubs for specialized projects or operations.

### 14. Maximum Experience by City
This query retrieves the maximum `ExperienceInCurrentDomain` for employees grouped by `City`. It identifies cities where employees have the most domain experience, which can be indicative of regional expertise and potential hubs for specialized projects or operations.

### 15. Average Age of PhD Employees Who Have Left
This query calculates the average `Age` of employees with `Education = 'PHD'` who have `LeaveOrNot = 1`. It provides insights into the age profile of highly educated employees who have left the organization, offering clues about retention challenges or career progression issues among this group.

This report outlines the diverse insights that can be gleaned from the `Employee_info` dataset through various SQL queries. Each query serves a specific analytical purpose, contributing to a holistic understanding of employee demographics, experiences, and organizational dynamics. These insights are crucial for informed decision-making in HR, strategic planning, and employee management within the organization.
