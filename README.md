# Pewlett Hackard Analysis

## Overview of Project
> Now that Bobby has proven his SQL chops, his manager has given both of you two more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age. 

1. ***Deliverable 1***: The Number of Retiring Employees by Title
2. ***Deliverable 2***: The Employees Eligible for the Mentorship Program
3. ***Deliverable 3***: A written report on the employee database analysis [`README.md`](https://github.com/DataJew/Pewlett-Hackard-Analysis). 


## Deliverable 1:  The Number of Retiring Employees by Title
### Deliverable Requirements:
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955. Because some employees may have multiple titles in the database—for example, due to promotions—you’ll need to use the `DISTINCT ON` statement to create a table that contains the most recent title of each employee. Then, use the `COUNT()` function to create a final table that has the number of retirement-age employees by most recent job title.

1. A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955 
2. The Retirement Titles table is exported as `retirement_titles.csv`
3. A query is written and executed to create a Unique Titles table that contains the employee number, first and last name, and most recent title.
4. The Unique Titles table is exported as `unique_titles.csv`  
5. A query is written and executed to create a Retiring Titles table that contains the number of titles filled by employees who are retiring. 
6. The Retiring Titles table is exported as `retiring_titles.csv`

 
### Results with detail analysis:

1. **A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955.**

2. **The Retirement Titles table is exported as `retirement_titles.csv`**

3. ​***A query is written and executed to create a Unique Titles table that contains the employee number, first and last name, and most recent title.**

4. **The Unique Titles table is exported as `unique_titles.csv`**

5. **A query is written and executed to create a Retiring Titles table that contains the number of titles filled by employees who are retiring.**

6. **The Retiring Titles table is exported as `retiring_titles.csv`**


## Deliverable 2: The Employees Eligible for the Mentorship Program
### Deliverable Requirements:
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.

1. A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.
2. The Mentorship Eligibility table is exported and saved as `mentorship_eligibilty.csv`

## Deliverable 3: A written report on the employee database analysis
### The analysis should contain the following:

1. **Overview** 
* Explain the purpose of this analysis.:

    > In this deliverable, Bobby was tasked to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.


2. **Results** 
* Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed:

    > * From the finding of the eligible retirees, a high percentage of the workforce could retire at any given time. 
    > * From the job titles of the eligible retirees, the breakdown is below.
    > * 32,452 Staff
    > * 29,415 Senior Engineer
    > * 14,221 Engineer
    > * 8,047 Senior Staff
    > * 4,502 Technique Leader
    > * 1,761 Assistant Engineer
    
**Image Below** 
    



3. **Summary** 
* Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami.":

    > **1)** How many roles will need to be filled as the "silver tsunami" begins to make an impact?.

    90,398 roles are in urgent need to be filled out as soon as the workforce starts retiring at any given time. 
     
    > **2)** Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?  

    No, we have 1,940 employees who are eligible to participate in a mentorship program. 

**Image Below** 
