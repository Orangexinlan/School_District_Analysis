# School_District_Analysis

## Overview of Project

### Purpose and Background
Analyze data on student funding and students' standardized test score. Based on the information about every student's math and reading scores as well as various information on the schools they attend. My task is to aggregate thebdata and showcase trends in school performance. This analysis will assist the school board and superintendent in masking decisions regarding school budgets and priorities.

Aditionally based on the dishonesty happened at nineth grade in Thomas High School, the school board wanted the data to be removed and see the comparison.

## Analysis and Results
We have few outputs, we recalculated Top Five and Bottom Five Schools, we have results based on School Size, School Types and Spending Budgets. We will analyze the differences between with or wothout the Nineth Grade in Thomas High Scool.

### District Analysit 

#### Original
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/Original%20District.png)
#### Updated
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/New%20District.png)

We can see by replacing NAN for the Ninth Grade Math and Reading score, the Reading Passing Percentage dropped 0.3%, and 0.2% for Math Passing Percnetatge. and 0.1% for Overall Passing Percentage.

### Top Five School

#### Original
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/Original%20Top%20School.png)
#### Updated
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/New%20top.png)

The ranking of the top schools was not affected. Even though both the score and percentage dropped for Thomas High School. The rest schools are stay still.

### Bottom Five School

#### Original
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/Original%20Bottom%20School.png)
#### Updated
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/New%20Bottom.png)

There's no change on this group.

### Math and Reading Score 

#### Original
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/original%20math.png)
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/original%20reading.png)
#### Updated
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/New%20Math%20Score.png)
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/new%20Reading%20score.png)

The only score that is impacted on this DataFrame is that the grade 9 students at Thomas High School have Nan instead of a grade for both math and reading.

### Impact on Scores by School Size

#### Original
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/5dcf9bffa9680e4ead79542430bd7d157a34691a/Resources/Original%20by%20School%20Size.png)
#### Updated
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/c942a9c469266af5cc19367a99bf191c6c59c608/Resources/New%20Size.png)

Only the scores for the Medium (1000-2000) size schools changed slightly (less than 1 percentage point as we have seen with other calculations above). 


### Impact on Scores by School Type

#### Original
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/c942a9c469266af5cc19367a99bf191c6c59c608/Resources/Original%20by%20School%20Type.png)
#### Updated
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/c942a9c469266af5cc19367a99bf191c6c59c608/Resources/New%20by%20School%20Type.png)

Thomas High School is a Charter type school, so the changed is slightly, not ever 0.1%. But no changes to District type school scores.

### Impact on Scores by School Spending

#### Original
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/c942a9c469266af5cc19367a99bf191c6c59c608/Resources/Original%20by%20Spending.png)
#### Updated
![this is an image](https://github.com/Orangexinlan/School_District_Analysis/blob/92a09b5aad924f680b6b2ca2658f60cf9291019d/Resources/New%20spending.png)

The change in the scores by school spending groups for the $630-644 per student grouping as this is where Thomas High School is grouped, however the change is small with each metric change of less than 0.1%.

## Summary
  1.District Analysis - changes to all scores by less than 0.5 percentage, there's no impact to school or student count.
  
  2.Top School Ranking - the ranking is not affected, however Thomas High School scores did change, but by less than 1 percentfor each metric.
  
  3.Scores by School Size - only change is on Medium (1000-2000) grouping for all scores by less than 0.1 percent.
  
  4.Scores by School Type - changes happened to Charter type grouping for all scores by less than 0.1 percent.
