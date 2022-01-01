# Pewlett-Hackard-Analysis


**Overview of the analysis****

​	The purpose of this analysis is to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program using postgres(PGAdmin).



**Results:**

- **Retirement Titles**

​		The table below shows the retirement by titles were we filter the data by employees and titles who were born between 1952 and 1955.

![retirement_titles](https://user-images.githubusercontent.com/94090097/147858372-a14b90fa-6ce3-4dd6-8361-1267d3979129.png)

- **Unique Titles**

  The table below shows the narrowed down list of the "retirement tables" were we remove out the duplicates and only query the most recent titles that the employees hold.

![unique_titles](https://user-images.githubusercontent.com/94090097/147858377-88648e66-6fd1-4f2a-9da3-cce5293dba1a.png)

- **Count of Retiring by Titles**

  The table below show the count or total number of employees retiring by titles.

![retiring_titles_by_count](https://user-images.githubusercontent.com/94090097/147858375-de2a43ed-2320-4ed6-a33a-2cfd3574be49.png)

- **Eligible for Mentorship**

​				The table below shows the eligible employees for mentorship were we filter the data by employees and titles who were born in 1965 and a total of 1550 employees.

![mentorship_eligibility](https://user-images.githubusercontent.com/94090097/147858379-f429c517-ae36-4dd5-b9ea-a8747c51d726.png)



**Summary:**

Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."

- How many roles will need to be filled as the "silver tsunami" begins to make an impact?

  There's a total of 90,398 employees in which roles needs to be fill before the "silver tsunami" or the employees born in 1952 to 1955 retiree.

  

- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

  Currently, there's a total of 1550 employees who meets the eligibility of mentorship criteria which was employees born in 1965. There's still a huge difference between number of employees retiring which 90,398 that still need to fill. I would suggest to expand the eligibility criteria to fill the remaining position from people who were born between 1965 to 1975.
