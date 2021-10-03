Pewlett-Hackard-Analysis

SQL, retirement, and job openings analyses

Overview

Bobby was tasked with analyzing how many employees are approaching retirement at Pewlett Hackard. Using existing employee data provided, Bobby was tasked with conducting an analysis using PostgreSQL and pgAdmin to see exactly how many employees would need to be hired, and for which departments, to replace the upcoming retirees. 

Results

Queries were developed to determine the number of retiring employees per title using the original csv data provided by HR that were then converted to tables. Three additional tables were created to obtain a list of current employees with unique and current titles, avoiding duplicates. Additional queries were created to identify employees who are eligible to participate in a mentorship program. This was done by using an INNER JOIN coupled with WHERE statements. 

Summary

90,398 roles will need to be filled as a result of the "silver tsunami" taking place at Pewlett Hackard and there are currently 56,859 qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. Additional queries could involve current employees on the verge of meeting mentorship eligibility as the next wave of new employee support or queries to identify department-based protégés in the pool of current employees that may be ready to be promoted despite their time at the company. 

