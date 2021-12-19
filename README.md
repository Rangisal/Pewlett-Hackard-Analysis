# Pewlett-Hackard-Analysis

# Overview of the analysis
  There are two main purposes of this project. 
  - Determining the number of retiring employees per title 
  - Identifying the employees who are eligible to participate in a mentorship program.
  The following ERD has been used to analyse the above two purposes.
  ![image](https://user-images.githubusercontent.com/93173498/146663845-076b8bf1-4c0f-4277-9311-6af3018017d0.png)

## Determining the number of retiring employees per title

- The retirement titles that holds the titles of employees who were born between January 1,1952 and December 31,1955. DISTINCT ON statement has been used to create the table that contains the most recent of each employee. Then used the COUNT() function to create the table that has the number of retirement age employees by most recent job title and excluded the employees who have already left the company.

- The exported  data from the above has been saved under unique_titles.csv and the file can be found in the following link.

   https://github.com/Rangisal/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv


- Then retiring_titles table has been created which includes the number of employees by their most recent job title which are about to retire. The file can be found in the    following ink. 

   https://github.com/Rangisal/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv
   

## Identifying the employees who are eligible to participate in a mentorship program
- The mentorship_eligibility table has been created with the current employees who were born between January 1,1965 and December 31,1965. The data have been retrieve from the employees table, department employees table and the title table. 
- The following link shows the above file's details. 

  https://github.com/Rangisal/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv


## Summary 
- According to the above analysis it shows that….of people are most likely  to retire in next 5-10 years. The company has to have a proper hiring plan in place and should allocate the enough funds for the process. 

  ![image](https://user-images.githubusercontent.com/93173498/146664342-bae41ddc-489f-4dc0-8717-258893d5766f.png)


- There are ………. Of employees are qualified to be working in the mentorship program and as a percengtage it will eb ……………..
 



