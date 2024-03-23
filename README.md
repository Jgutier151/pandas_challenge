# School Data Analysis Project

# Introduction

In this project, I leveraged Pandas DataFrames and Jupyter Notebook to analyze school and standardized test data. The primary objective was to aggregate the district-wide standardized test results and present key trends in school performance. Using Pandas, I created a comprehensive report that includes various data points to showcase the educational landscape of the district.

# Key Metrics Analyzed

# District Summary
I calculated and created a high-level snapshot of the district's key metrics in a DataFrame, including:

Total number of unique schools
Total students
Total budget
Average math score
Average reading score
Percentage passing math
Percentage passing reading
Percentage overall passing

# School Summary
I summarized key metrics about each school, including:

School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
Percentage passing math
Percentage passing reading
Percentage overall passing

# Top Performing Schools
I sorted the schools by % overall passing in descending order and displayed the top 5 performing schools in a DataFrame called "top_schools".

# Lowest Performing Schools
I sorted the schools by % overall passing in ascending order and displayed the bottom 5 performing schools in a DataFrame called "bottom_schools".

# Math and Reading Scores by Grade
I created DataFrames listing the average math and reading scores for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Scores by School Spending
I analyzed school performance based on average spending ranges per student. I categorized spending into four bins and calculated mean scores per spending range, presenting the results in a DataFrame called "spending_summary".

# Scores by School Size
I categorized schools into small, medium, and large based on their total number of students and created a DataFrame called "size_summary" to analyze school performance based on size.

# Scores by School Type
Using the per_school_summary DataFrame, I created a new DataFrame called "type_summary" to showcase school performance based on school type.

# Tools and Techniques Used

Pandas: For data manipulation and analysis.
Jupyter Notebook: For interactive development and documentation.
Python: Programming language used for scripting and analysis.

# Conclusion
This project provided valuable insights into the district's educational performance and allowed for informed decision-making. By analyzing key metrics at both the district and school levels, stakeholders can better understand areas of strength and areas needing improvement, ultimately working towards enhancing educational outcomes.

