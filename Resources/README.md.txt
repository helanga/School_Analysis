
# School District Analysis Jupyter Notebook

## Overview of School District Analysis

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. 
Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. 
She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. 
Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Results

- How is the district summary affected?
 -Before Removing Thomas High School 9th grade records District Summery Report:
  ![](Resources\images\District_summery)

 - After removing Thomas High School 9th grade records District Summery:
  ![](Resources\images\Repeated_District_summery)
considering above reports we can say it didn't effected for "Average Math Score" and "Average Reading Score". 
Pasing math % and PAssing Reading % has reduced .1%.
And Overall Passing Precentage reduced by 1%

- How is the school summary affected?
 - School Summery Report before removing Thomas High School 9th grade records
  ![](Resources\images\PerSchoolSummerybefRepeating.png)
 
 - School Summery Report after removing Thomas High School 9th grade records
  ![](Resources\images\PerSchoolSummeryaftRepeating)

Afetr comparing above reports we can see thomas High school's Passing Math%,Passing Reading% & Overall Passing % significantle increased.
  - Passing Math% has been increased from 66.9% to 93%
  - Passing Reading % has been increased from 69.6% to 97%
  - Overall PAssing % has been increased from 65.07 % to 90%

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

 - Top Perfoming Schools Report before removing Thomas High School 9th grade records
   ![](Resources\images\PerSchoolSummerybefRepeating)

 - Top Perfoming Schools Report after removing Thomas High School 9th grade records
   ![](Resources\images\PerSchoolSummeryaftRepeating)
considering above figures we can say that after removing Thomas high school 9 th grade records still it's second place out of top 5 achools.
but average scores and precentage wise figures has been reduced for Thomas High School.

- How does replacing the ninth-grade scores affect the following
  -Passing Reading
 - Math and reading scores by grade
   - Math Score by Grade
     Before replacing 9th Grade scores Math Score : After replacing 9 th Grade scores Math Score

    ![](Resources\images\MathScorebyGradebefore) ![](Resources\images\mathScorebyGradeafter)
  
    For Thomas High School MAth score it shows "nan" ,other than that there is no difference

   - Reading Score by Grade
     Before replacing 9th Grade scores, Reading Score : After replacing 9 th Grade scores, Reading Score
   
    ![](Resources\images\ReadingScorebyGradebefore) ![](Resources\images\ReadingScorebyGradeafter)

 - Scores by school spending

  If we consider before formating dataframes for scores by school spending,In $630-$644 group we can see slight difference in all scores and precentages.
  Before replacing Thomas High School Records : 
  ![](Resources\images\spendingsummerybefformat)
 Aftra replacing Thomas High School Records:
 ![](Resources\images\spendingsummeryafterformat)

But after formating dataframes both has same figures.
   
 - Scores by school size
  Before replacing 9th Grade scores,Scores by school size
![](Resources\images\schoolSizeSummerybef)

  After replacing 9th Grade scores,Scores by school size
 - Scores by school type
![](Resources\images\schoolSizeSummeryaft)

According to the above figures,we can say only Medium(1000-2000) size schools figures which Thmas High school belaongs has slight different.

#Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

 1)
 2)
 3)
 4)
























