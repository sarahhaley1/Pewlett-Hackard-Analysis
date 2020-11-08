# Pewlett-Hackard-Analysis
SQL

## Overview

### Purpose
The purpose of the Pewlett-Hackard-Analysis is to go through the company's employement records which are stored in different CSV files, and create SQL chops of the data within different files to be able to group the data in whichever way is condusive to our analysis. The purpose of this analysis in particular is to identify the many employees that are approaching retirement age based on their birthday, and retrieveing their roles within the company in order to find the positions in which are going to need a replacement once the employees retire. In order to retrieve the information we want, we have to create a table with the number of retiring employees by the most recent title of the employee within the company, and then get the count on each title of how many employees wihtin that field are retiring. There is also the need of the mentorship program in order to transition the retiring employees out of their roles. There is another table that is made that shows the employees who are currently working at the company and are eligible to be mentors in the mentorship program, this is to help them stay successful.

## Results

#### Retirement information

- Retiring titles
  - There are currently 8 titles that have retiring employees. The titles are : Senior Engineer, Senior Staff, Engineer, Staff, Technique Leader, Assistant Engineer, and Manager.

- Retiring employees count
  - There are a different number of employees retiring in each title
  - Senior Engineer : 22772
  - Senior Staff : 22000
  - Engineer : 19997
  - Staff : 18497
  - Technique Leader : 4501
  - Assistant Engineer : 2628
  - Manager : 3
  
 #### Mentorship Eligibility
 
 - Mentorship Elibile Titles
  - There are currently only 6 titles that have employees who are eligible to mentor. The titles are:
    - Staff
    - Senior Engineer
    - Engineer
    - Senior Staff
    - Technique Leader
    - Assistant Engineer
  
  - Mentorship Eligibility count
    - There are fewer mentorship eligible employees than there are retiring employees as well missing any one eligible for mentoring with title of Manager. 
    - This result tells us that they are not prepared for the "Silver Tsumani".
   
   
## Summary
Throughout this analysis it is shown that there are a large number of retiring employees, hence the "Silver Tsunami". The company will need to fill a large sum of roles in order to cover the impact that the retiring community will have on the company. In order to fill the positions of those retiring, the company will need to hire 22772 Senior Engineers, 22000 Senior Staff members, 19997 Engineers, 18497 Staff members, 4501 Technique Leaders, 2628 Assistant Engineers and 3 Managers. This is going to be done with the help of the employees who are eligible to partake in the mentorship program, however, there are not enough mentors to cover all of the positions that need to be filled. There needs to be managers at Pewlett Hackard who can mentor new managers, and there are not enough of the other titles to mentor the sum of positions that need to be filled.
    
    
  
    
    
