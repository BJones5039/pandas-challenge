# pandas-challenge

**Overview**
Welcome to the Pandas Challenge! In this assignment, you will leverage the power of Pandas DataFrames to analyze school and standardized test data for your city's school district. As the newly appointed Chief Data Scientist, your primary responsibility is to assist the school board and mayor in making informed decisions about future school budgets and priorities.

**Background**
As the Chief Data Scientist, your initial task involves a comprehensive analysis of district-wide standardized test results. You will have access to data containing math and reading scores for each student, along with various information about the schools they attend. The goal is to aggregate this data and uncover key trends in school performance.

**District Summary**
Perform the following calculations and create a high-level snapshot of the district's key metrics in a DataFrame:
- Total number of unique schools
- Total students
- Total budget
- Average math score
- Average reading score
- % passing math, % passing reading, % overall passing

**School Summary**
Create a DataFrame summarizing key metrics about each school:

- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score, average reading score
- % passing math, % passing reading, % overall passing

**Highest-Performing Schools**
Sort schools by % Overall Passing in descending order, display the top 5 rows.

**Lowest-Performing Schools**
Sort schools by % Overall Passing in ascending order, display the top 5 rows.

**Math Scores by Grade**
Create a DataFrame listing the average math score for students in each grade level (9th, 10th, 11th, 12th) at each school.

**Reading Scores by Grade**
Create a DataFrame listing the average reading score for students in each grade level (9th, 10th, 11th, 12th) at each school.

**Scores by School Spending**
Analyze school performance based on average spending ranges per student.

**Scores by School Size**
Analyze school performance based on school size. 

**Scores by School Type**
Analyze school performance based on school type. 

**Data Overview and Insights**

**Overview**: The dataset contains 15 different schools with a total of 39,170 students. The overall budget for all of these schools is about $24.65 million. On average these students score about 78 in math and 81 in reading. Overall 65% percent of this students are passing both subjects with at least a 70 or higher.

**Insight #1**- Schools with the lowest spending budgets per student tend to have the largest amount of students that passing both subjects overall with a 90% passing rate of a 70 or higher. Where as schools with the largest per student budget had the lowest overall passing at 53%.

**Insight #2** - Charter shcools has the highest scores and passing percentage scores when compared to District type schools.