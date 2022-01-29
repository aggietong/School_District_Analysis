# School_District_Analysis
# Challenge #4 (UTOR-VIRT-DATA-PT-12-2021-U-B)
# Student: Agnes Tong

## Overview of the Analysis

The original analysis was to provide the school board with some key indicators for each school. 
  •	Top 5 and bottom 5 performing schools, based on the overall passing rate
  •	The average math score received by students in each grade level at each school
  •	The average reading score received by students in each grade level at each school
  •	School performance based on the budget per student, school size, and type of school

It was suspected that there had been academic dishonesty from the grade 9 students at Thomas High School. The school board would like to replace the reading and writing scores for these students with “NaN” and determine whether there are any impacts to the overall results. 

## Results

The first table is the original analysis. 

<img width="394" alt="All_Schools" src="https://user-images.githubusercontent.com/96399622/151647956-ee2429e4-b12a-4b19-8ebf-87efa9dfd4d4.PNG">


The second table shows the results without Thomas High School’s grade 9 student’s math and reading scores. 

<img width="449" alt="All Schools Without ninth grade Thomas School" src="https://user-images.githubusercontent.com/96399622/151647960-6bdaca27-ec69-4413-b275-a4bd86bfe981.PNG">


•	Overall, the results for the district were largely unaffected, as only a small subset of scores were replaced with “NaN. This function is a common way to represent missing value. 
•	At the school level, Thomas High School’s average math and reading scores, % passing math, % passing reading, and overall % passing were minimally affected. There was a 0.33% decrease in overall % passing between the original and second analysis.
•	Thomas High School remains the second highest performing school. The original analysis had an overall % passing of 90.95% vs 90.63% in the second analysis. 
•	There was also almost no impact for scores by school spending and scores by school size, and scores by school type, and math and reading scores by grade. 


## Summary

The removal of the grade 9 data from Thomas High School had minimal impact on the analysis. We did see <0.5% changes in the average math and reading scores, % passing for math and reading, and % overall passing. The School board can be confident that by removal of the grade 9 data should not skew the data in the district analysis. 
