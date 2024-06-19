# pandas-challenge
#                                                                   PyCitySchools

![education](https://github.com/EvgeniiaKei/pandas-challenge/assets/166274251/96ba9a29-f126-4c86-a5aa-178b544afdcc)

# Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.
Hint: Check out the sample solution called PyCitySchools_starter.ipynb located in the .zip file to review the desired format for this assignment.

# Local Government Area (LGA) Summary
Perform the necessary calculations and then create a high-level snapshot of the local government area's key metrics in a DataFrame.
Include the following:
Total number of unique schools
Total students
Total budget
Average maths score
Average reading score
% passing maths (the percentage of students who passed maths)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed maths AND reading)
Note: A passing grade is 50 or higher.

# School Summary
Perform the necessary calculations and then create a DataFrame that summarises key metrics about each school.

Include the following:
School name
School type
Total students
Total school budget
Per student budget
Average maths score
Average reading score
% passing maths (the percentage of students who passed maths)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed maths AND reading)

# Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top_schools".

# Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".

# Maths Scores by Year
Perform the necessary calculations to create a DataFrame that lists the average maths score for students of each year level (9, 10, 11, 12) at each school.
# Reading Scores by Year
Create a DataFrame that lists the average reading score for students of each year level (9, 10, 11, 12) at each school.

# Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student). Use the code provided below to create four bins with reasonable cutoff values to group school spending.

# Scores by School Size
Use the following code to bin the per_school_summary. Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.
Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

# Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.This new DataFrame should show school performance based on the "School Type".

# Data Analysis Report
From the collected data we can conclude that higher spending (per student), doesn't result in higher test scores.  It can also be concluded that  small (<1000) schools have better overall passing then large (2000-5000) schools. Summariing all the above points, we can conclude that the most effective school with average costs is Griffin Hight school. 


<img width="544" alt="Grif" src="https://github.com/EvgeniiaKei/pandas-challenge/assets/166274251/e415d5ac-18dd-4fd2-9bb8-d0dae683e375">


Trends:
1. Independent Schools are better placed to achieve higher passing grades on average.(please check the data (type_summary.mean())
2. The results of scores by School Spending and the scores by School Size, the top performing schools have some of the lowest number of total students. Smaller schools with smaller per student budgets perform better in comparison with bigger schools with greater per student budgets.

