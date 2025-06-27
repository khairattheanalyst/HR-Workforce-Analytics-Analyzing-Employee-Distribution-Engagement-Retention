![Employee Dashboard Analysis 1](https://github.com/user-attachments/assets/e1983948-01c1-4a32-91a5-965659972602)

![Employee Dashboard Analysis 2](https://github.com/user-attachments/assets/5a57d23f-25cf-482b-83d4-48826b2b5d33)

**INTRODUCTION**

This report presents a data-driven analysis of employee records to support strategic decision-making within the Human Resources (HR) function. The dataset contains comprehensive information on both current and former employees, including demographics, employment status, job roles, departmental affiliations, and performance indicators. It spans multiple divisions and employment types, providing a holistic view of the organization’s workforce.

The analysis is tailored for HR Managers, the primary stakeholders responsible for managing employee lifecycles, identifying workforce trends, and improving retention strategies. For these stakeholders, success means having clear, accurate insights into the structure, performance, and movement of the workforce to enable informed planning and efficient management.

By leveraging this dataset, the report aims to uncover patterns and insights that will assist HR in optimizing talent strategy, enhancing employee experience, and sustaining organizational growth.

**DATA PREPROCESSING**

Before analysis, the dataset underwent a thorough cleaning process to ensure data quality, consistency, and accuracy. The steps taken included both structural and contextual refinements using Power Query and DAX within Power BI.

1. I removed duplicate columns and dropped irrelevant fields that were not useful for the analysis.
2. I merged the First Name and Last Name columns to create a unique full name identifier for easier referencing in visuals.
3. Blank rows were removed, and I handled missing values using appropriate logic depending on the context of each field.
4. Data types were standardized, for example, dates were properly formatted and numerical fields corrected where needed.
5. Categorical variables like gender, race, and marital status were cleaned and normalized to ensure consistency.
6. I used Date of Birth to calculate each employee's age and then grouped them into clearly defined age brackets.
7. Using the Start and Exit Dates, I calculated how many days each employee stayed with the company. For active employees, I accounted for the lack of an exit date using a fixed reference point.
8. Duplicate employee records were checked and removed using Employee ID and full name combinations.
9. Obvious outliers and incorrect values, such as negative days worked, were flagged and either corrected or excluded from the analysis.
10. I trimmed hidden characters and unnecessary spaces from text fields to avoid issues with filters and slicers later on.
11. Lastly, I reviewed the data relationships and ensured the fields were well-prepared for dashboard modeling and clean interactions.

**Industry Type of Dataset**

Human Resources (HR) / Workforce Management

**Stakeholders of the Analysis**

HR Managers - They are responsible for overseeing employee data, managing workforce trends, and making informed decisions on hiring, retention, and performance

**What Success means to the Stakeholders**

Success for HR Managers means having clear, accurate insights into the workforce to support strategic planning. It includes understanding employee demographics, performance, and turnover to improve retention and efficiency.

**Data Limitations or Biases:** None

**PRE-ANALYSIS OVERVIEW**

To guide the analysis and uncover meaningful patterns, a set of targeted questions was developed based on the dataset structure and stakeholder needs. These questions focused on understanding employee distribution, performance trends, termination patterns, and demographic insights. The findings derived from these questions provided valuable observations that informed the final recommendations and strategic considerations.

**Potential Analysis Questions**
1. What is the count of employees by employee status?
2. How are employees distributed by gender?
3. How are employees distributed by race description?
4. How many employees are terminated each month?
5. Which departments have the highest number of employees?
6. What is the average employee rating in each pay zone?
7. How does performance score vary by marital status?
8. Which employment type has the highest concentration, and what is the average performance rating for each type?
9. Who are the longest-serving employees based on their start and exit dates?
10. What are the top reasons for employee exits, based on termination type?
11. How are employees distributed across different age groups?
12. What is the relationship between employee termination type and employee classification type?

**READ THE FULL REPORT ON MEDIUM:** https://medium.com/@Khairattheanalyst/hr-workforce-analytics-analyzing-employee-distribution-engagement-retention-2872b808879d
