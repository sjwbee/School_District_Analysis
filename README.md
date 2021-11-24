# School District Analysis

## Purpose

The purpose of this project was to read and analyze student data in the students_complete.csv file as well as the corresponding schools_complete.csv file to investigate the relationship between school budgets and student success outcomes in reading and math. 

Using the Anaconda package, I used the pandas library and jupyter notebook to clean and manipulate my data and construct dataframes that would facilitate comparison across multiple schools. 

With suspected cheating which could influence the results of the analysis, I set scores from "Thomas High School's" 9th grade class equal to NaN or "Not a Number" and repeated the analysis to observe the extent to which cheating may have influenced the results. 

## Results
### Before 9th grade Thomas High School scores were changed
-District Summary
The District Summary was created by:
 1. combining the school data and student data into one dataset 
<img width="973" alt="Screen Shot 2021-11-23 at 3 38 15 PM" src="https://user-images.githubusercontent.com/90734050/143145892-6aef1380-b714-4711-b2e8-9e7e6183b21b.png">

 2. calculating the totals of schools, students, and budget 
<img width="961" alt="Screen Shot 2021-11-23 at 3 41 00 PM" src="https://user-images.githubusercontent.com/90734050/143146003-e640d343-ab14-4724-86f6-d69a229516a3.png">

 3. determining the averages of math and reading scores 
 <img width="946" alt="Screen Shot 2021-11-23 at 3 41 54 PM" src="https://user-images.githubusercontent.com/90734050/143146075-2892f11d-cf8c-4173-b999-e797c2c5135d.png">

 4. determining the overall passing score
 <img width="1008" alt="Screen Shot 2021-11-23 at 3 44 48 PM" src="https://user-images.githubusercontent.com/90734050/143146275-d8ea347d-fba0-40a0-89cd-3d6b1c5c4c8d.png">
 
 The outcome of the District Summary looks like this:
 <img width="1103" alt="Screen Shot 2021-11-23 at 4 00 29 PM" src="https://user-images.githubusercontent.com/90734050/143147432-165066f4-20f0-4c16-9948-9414abe7c144.png">


 
 -School Summary
 The School Summary was created by:
 1. Determining school type
 2. Calculating the number of students in each school
 3. Calculating the school budget and the budget per student
 4. Calculating average test scores
 5. Calculating the percentage of students passing math, reading, and overall

<img width="1008" alt="Screen Shot 2021-11-23 at 3 49 43 PM" src="https://user-images.githubusercontent.com/90734050/143148149-0ec5940f-3b32-4e27-9aa2-7b7c939b6851.png">


The outcome of the School Summary looks like this:
<img width="1103" alt="Screen Shot 2021-11-23 at 4 06 14 PM" src="https://user-images.githubusercontent.com/90734050/143148045-066578f8-a30d-4a2d-9610-fcb5060d78b9.png">


### After 9th grade Thomas High School scores were changed

District Summary:
<img width="1008" alt="Screen Shot 2021-11-23 at 3 54 07 PM" src="https://user-images.githubusercontent.com/90734050/143147336-5ab3ce20-4866-433c-8f9f-b698e4f1a7a2.png">

School Summary:
<img width="1103" alt="Screen Shot 2021-11-23 at 4 16 42 PM" src="https://user-images.githubusercontent.com/90734050/143148784-e0943561-520c-4721-8212-6bc2ad877143.png">

### Before and after: How has it changed?

There is a slight reduction in passing math and reading % after the 9th grade scores have been changed to NaN, but only by a fraction of a percentage point indicating the 10th-12th grade scores are similar to that of the 9th grade scores. Overall there does not appear to be a significant difference before and after the scores were changed. 

### Effects of changes:

-By grade:
  The new results show NaN in the 9th grade column of Thomas High School
  
-Scores by School Spending:
  Thomas High School fell into the $630-$644 spending per student bin. The change in 9th grade scores did not affect the results in the bin in a significant way.
  
-Scores by School Size:
  Thomas High School fell into the "Medium" class size at between 1000 to 2000 students. Then change in 9th grade scores did not affect the results in a significant    way.
  
-Scores by School Type:
  Thomas High School fell into the "Charter" school category. The change in scores did not affect the scores by school type in a significant way. 
 
## Summary

The change in scores for Thomas High School's 9th grade class due to suspected cheating did not significantly change the outcome for scores by grade, school spending, school size, or school type. The changes that did occur, only decreased the school's scores and passing percentages by a fraction that was not discernable when scores were formatted to round to the nearest whole or tenths of a percentage. This is likely because the nulled values were similar to the scores that Thomas High School's 10th through 12th grade classes had. 

 
