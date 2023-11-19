# Pandas-Challenge | Assignment - PyCitySchools

## Summary Analysis:
The task involves analyzing school and student data in PyCitySchools using Pandas in Python to derive various metrics and summaries. Here's a breakdown of the requirements:

**District Summary (20 points):**
- Calculate total unique schools, total students, total budget, average math score, average reading score, % passing math, % passing reading, and % overall passing. Create a DataFrame named "district_summary" with these calculations.

**School Summary (20 points):**
- Calculate metrics for each school: total students, total school budget, per student budget, average math score, average reading score, % passing math, % passing reading, and % overall passing. Create a DataFrame named "per_school_summary" with these calculations.

**Highest-Performing and Lowest-Performing Schools (by % Overall Passing) (10 points):**
- Sort schools by % Overall Passing in descending order to create a DataFrame named "top_schools" displaying the top 5 schools.
- Sort schools by % Overall Passing in ascending order to create a DataFrame named "bottom_schools" displaying the bottom 5 schools.

**Math Scores by Grade (10 points):**
- Calculate average math scores for each grade level (9th, 10th, 11th, 12th) at each school. Combine these scores into a DataFrame named "math_scores_by_grade".

**Reading Scores by Grade (10 points):**
- Calculate average reading scores for each grade level (9th, 10th, 11th, 12th) at each school. Combine these scores into a DataFrame named "reading_scores_by_grade".

**Scores by School Spending (5 points):**
- Categorize school spending per student into ranges using provided bins. Calculate average math score, average reading score, % passing math, % passing reading, and % overall passing for each spending range. Create a DataFrame named "spending_summary" with these metrics.

**Scores by School Size (5 points):**
- Categorize schools into size ranges using provided bins. Calculate average math score, average reading score, % passing math, % passing reading, and % overall passing for each size range. Create a DataFrame named "size_summary" with these metrics.

**Scores by School Type (5 points):**
- Group schools by school type (charter or district). Calculate average math score, average reading score, % passing math, % passing reading, and % overall passing for each school type. Create a DataFrame named "type_summary" with these metrics.

These tasks require calculating various metrics using Pandas functions, grouping and aggregating data, creating bins for categorization, and creating DataFrames to summarize the information for further analysis and decision-making.

**Written Report (15 point):**
- Summary Analysis
- Conclusions from the calculations

**Note: This report will be seen at Readme file on this repository!**
  
## Conclusions:
These conclusions highlight the influence of school type and size on performance, as well as the intriguing lack of direct correlation between spending and academic achievement, suggesting that factors beyond financial resources contribute significantly to student success.

**Performance Discrepancies Among Schools:**
- There was a noticeable difference in performance between charter schools and district schools. Charter schools tended to perform better in terms of overall passing rates and average scores in math and reading compared to district schools.
- Schools with a smaller student population tended to have higher overall passing rates and average scores compared to larger schools. This indicates that smaller class sizes might positively impact academic performance.

**Impact of School Spending on Academic Performance:**
- There was no significant correlation found between per-student spending and academic achievement. Schools that spent more per student did not necessarily yield better academic results.
- Interestingly, schools with lower per-student spending sometimes showcased higher passing rates and average scores, challenging the assumption that increased funding directly translates to improved academic outcomes.
