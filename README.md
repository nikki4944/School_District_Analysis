# School District Analysis
Module 4 Challenge

## Project Overview

The client, a district school board, has requested an analysis of standardized test scores for all of the schools in the district which they will use to determine how funds are allocated in the next year's budget. For this analysis, the data consists of math and reading scores for all grade levels (9th-12th) from the 15 schools (both charter and district) which make up the district.

The data was analyzed to find the each school's average math and reading score as well as the passing percentage of each and the overall passing percentage. The data was futher filtered to provide results for each of the four grade levels, size of student population, amount of budget spent per student, and the type of school (district vs. charter).

After performing the analysis, the school board communicated a potential problem with the data reported for 9th graders at Thomas High School. Another analysis was performed which removed these scores from the final deliverable.

## Results

As the first step of this analysis, a DataFrame was created to combine the information from the two data sets into one which forms the basis of all filtered analyses done later. 

The following DataFrame shows the School Type, School Budget, Per Student Budget, Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing for each of the 15 schools in the district.

<img width="1015" alt="Original Per School" src="https://user-images.githubusercontent.com/82982901/119191683-fb388c00-ba4c-11eb-957d-a7e4b80bd807.png">

Following guidance from the school board which raised questions about the reported grades for 9th graders at Thomas High School, the DataFrame was adjusted to remove these grades from the analysis. As the following shows, slight differences can be detected in the last five columns of the Thomas High School row.

<img width="1016" alt="Re-analysis Per School" src="https://user-images.githubusercontent.com/82982901/119192131-9c274700-ba4d-11eb-8f0a-45c1f01b862b.png">

###### Overall District Comparision

Removing the 9th grade scores from Thomas High School had minimal affect on how the school compared to others in the district. In both analyses, the five highest performing schols were charter schools with smaller student populations while the lowest performing schools were district schools with large student populations. Thomas High School appeared in the top five performers list in both analyses and both tables are displayed below.
* Original highest performing schools DataFrame
<img width="995" alt="Original Highest Schools" src="https://user-images.githubusercontent.com/82982901/119195959-713ff180-ba53-11eb-8d21-61d67db829e6.png">

* DataFrame with Thomas High School's 9th grade scores removed
<img width="801" alt="Re-analysis Highest Schools" src="https://user-images.githubusercontent.com/82982901/119195967-74d37880-ba53-11eb-97eb-8b9658cd08c9.png">

* DataFrame showing the lowest performing schools
 <img width="995" alt="Original Highest Schools" src="https://user-images.githubusercontent.com/82982901/119196201-cbd94d80-ba53-11eb-9a8a-a9a29b5d1205.png">

###### Analysis by Grade

As part of the deliverable, the math and reading scores were compared by school and separated out by grade as shown in the following DataFrames from the original analysis.

* Math scores by grade
<img width="328" alt="Original by Math" src="https://user-images.githubusercontent.com/82982901/119197053-2d4dec00-ba55-11eb-9ccc-2f4b1138342c.png">

* Reading scores by grade
<img width="336" alt="Original by Reading" src="https://user-images.githubusercontent.com/82982901/119197147-4e164180-ba55-11eb-92e3-3fa680cb04f0.png">

In this part of the overall project, a change can be detected in the results as Thomas High School does not have any data calculated for the 9th grade.

* Math scores by grade
<img width="315" alt="Re-analysis Math by Grade" src="https://user-images.githubusercontent.com/82982901/119197388-a64d4380-ba55-11eb-8754-de0df5afd2ec.png">

* Reading scores by grade
<img width="320" alt="Re-analysis by Reading" src="https://user-images.githubusercontent.com/82982901/119197417-ae0ce800-ba55-11eb-8d46-b61a4ae1db26.png">

###### Analysis by School Spending, Size, and Type 

Additionally, the deliverable also filtered the data sets and analyzed the scores by school spending per student, school size, and school type. The code for these three analyses did not utilize individual grade data and the results where unchanged. The following illustrates the results:

* Schools who spent more money per student actually performed less well overall on the standardized tests.

<img width="798" alt="Re-analysis by Student Spending" src="https://user-images.githubusercontent.com/82982901/119194292-dcd48f80-ba50-11eb-8775-899acd1eb07b.png">

* Schools with larger populations averaged the lowest scores and have the lowest overall passing percentage.

<img width="766" alt="Re-analysis by Size" src="https://user-images.githubusercontent.com/82982901/119194309-e231da00-ba50-11eb-98de-891d338160cd.png">

* Charter schools with smaller student populations, as illustrated in the original per school DataFrame, performed the best across the board.

<img width="712" alt="Re-analysis by Type" src="https://user-images.githubusercontent.com/82982901/119194324-e6f68e00-ba50-11eb-8ea4-7f0bae2b56f9.png">


## Summary

After removing Thomas High School's 9th grade score date from the analysis, slight changes were apparent in the average math and reading scores and the percentages calculated. 
* The average math score changed from 83.41 to 83.35 
* The average reading score changed from 83.85 to 83.89 
* The passing math percentage changed from 93.27 to 93.19 
* The passing reading percentage changed from 97.31 to 97.02 
* The overall passing percentage changed from 90.95 to 90.63

These changes had no effect on Thomas High School's high perfomance rate, they were the 2nd hightest performing school in the original analysis as well as the re-analysis.

A further analysis which takes into consideration average class size and number of teachers at each school would be recommended in order to gain greater understanding of how larger schools with more per student spending received the lowest test scores.
