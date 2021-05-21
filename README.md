# School District Analysis
Module 4 Challenge

## Project Overview

The client, a district school board, has requested an analysis of standardized test scores for all of the schools in the district which will they will use to determine who they allocate funds in the next year's budget. For this analysis, the data consists of math and reading scores for all grade levels (9th-12th) from the 15 schools (both charter and district) which make up the district.

The data was analyzed to find the each school's average math and reading score as well as the passing percentage of each and the overall passing percentage. The data was futher filtered to provide results for each of the four grade levels, size of student population, amount of budget spend per student, and the type of school (district vs. charter).

After performing an analysis, school board reported a potential problem with the data reported for 9th graders at Thomas High School. Another analysis was performed which removed these scores from the final deliverable.

## Results

As the first step of this analysis, a DataFrame was created to combine the information from the two data sets into one which forms the basis of all filtered analyses done later. 

The following DataFrame shows the School Type, School Budget, Per Student Budget, Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing for each of the 15 schools in the district.

<img width="1015" alt="Original Per School" src="https://user-images.githubusercontent.com/82982901/119191683-fb388c00-ba4c-11eb-957d-a7e4b80bd807.png">

Following guidance from the school board which raised questions about the reported grades for 9th graders at Thomas High School, the DataFrame was adjusted to remove these grades from the analysis. As the following shows, the only school effected by this change was Thomas High School where a slight difference can be detected in the last five columns.

<img width="1016" alt="Re-analysis Per School" src="https://user-images.githubusercontent.com/82982901/119192131-9c274700-ba4d-11eb-8f0a-45c1f01b862b.png">



## Summary

After removing Thomas High School's 9th grade score date from the analysis, slight changes were apparent in the average math and reading scores and the percentages calculated. 
* The average math score changed from 83.41 to 83.35 
* The average reading score changed from 83.85 to 83.89 
* The passing math percentage changed from 93.27 to 93.19 
* The passing reading percentage changed from 97.31 to 97.02 
* The overall passing percentage changed from 90.95 to 90.63

These changes had no effect on Thomas High School's high perfomance rate, they were the 2nd hightest performing school in the original analysis as well as the re-analysis.
