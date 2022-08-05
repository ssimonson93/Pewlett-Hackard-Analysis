# Overview of Analysis
This project was conducted in order to determine how many employees at Pewlett Hackard are likely to retire in the upcoming few years, as well as which titles these employees hold to determine what positions will need to be filled.  Current employees with birth dates between 1952 and 1955 were separated out from the total number of past and present employees to provide Pewlett Hackard with a database of employees who are eligible for their retirement package.

# Results
The following information was found after filtering and analyzing the employment data for retirement eligible employees.
* The first query performed on the employment data filtered for all current employees born between 1952 and 1955, and found 133,776 results for employees eligible for the retirement package.
* Further analysis was done to remove duplicate individuals from this list of employees, and ultimately 72,458 retirement eligible employees were found.
* Specifically, Figure 1 below shows a table of how many of these employees hold which titles.  The greatest number of eligible retirees are Senior Engineers, while the least number of eligible retirees are Managers.
* Current employees born in 1965 were also filtered out of the employment data to find how many employees will be available to participate in Pewlett Hackard’s mentorship program.  This table found 1,549 employees are eligible to be mentors.

## Figure 1

![This is an image](https://github.com/ssimonson93/Pewlett-Hackard-Analysis/blob/main/Retirees%20by%20Title.PNG)

# Summary
These findings can help Pewlett Hackard plan their best for the future in a few ways.  First, as mentioned in the results section, a table was generated showing which retirement eligible employees hold which positions in the company.  This table can be queried in pgAdmin using “SELECT * FROM retiring_titles” and shows the vast majority of roles being potentially vacated are Senior Engineers and Senior Staff.  Pewlett Hackard will need to plan to fill over 50,000 of these two positions as the “silver tsunami” begins to take place.  Also, the 1,549 eligible mentors found is significantly outnumbered by the 72,458 employees eligible to retire.  This number is quite unlikely to be able to handle the influx of new employees hired to replace the retirees, and Pewlett Hackard may want to expand their eligibility parameters for their mentorship program.
