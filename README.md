# pandas-challenge

Overview
Welcome to the Pandas Challenge! In this assignment, you will leverage the power of Pandas DataFrames to analyze school and standardized test data for your city's school district. As the newly appointed Chief Data Scientist, your primary responsibility is to assist the school board and mayor in making informed decisions about future school budgets and priorities.

Background
As the Chief Data Scientist, your initial task involves a comprehensive analysis of district-wide standardized test results. You will have access to data containing math and reading scores for each student, along with various information about the schools they attend. The goal is to aggregate this data and uncover key trends in school performance.

District Summary
Perform the following calculations and create a high-level snapshot of the district's key metrics in a DataFrame:

Total number of unique schools
Total students
Total budget
Average math score
Average reading score
% passing math, % passing reading, % overall passing
Save the results in a DataFrame called "district_summary."

School Summary
Create a DataFrame summarizing key metrics about each school:

School name
School type
Total students
Total school budget
Per student budget
Average math score, average reading score
% passing math, % passing reading, % overall passing
Save the results in a DataFrame called "per_school_summary."

Highest-Performing Schools
Sort schools by % Overall Passing in descending order, display the top 5 rows, and save the results in a DataFrame called "top_schools."

Lowest-Performing Schools
Sort schools by % Overall Passing in ascending order, display the top 5 rows, and save the results in a DataFrame called "bottom_schools."

Math Scores by Grade
Create a DataFrame listing the average math score for students in each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Create a DataFrame listing the average reading score for students in each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
Analyze school performance based on average spending ranges per student. Use predefined bins and labels to categorize spending. Calculate mean scores per spending range and create a DataFrame called "spending_summary."

Scores by School Size
Analyze school performance based on school size. Use predefined bins and labels to categorize school size. Calculate mean scores per size range and create a DataFrame called "size_summary."

Scores by School Type
Analyze school performance based on school type. Group the per_school_summary DataFrame by "School Type" and create a DataFrame called "type_summary."