# School_District_Analysis

## Project Overview
The purpose for this project was to delete math and reading scores of Thomas High School ninth graders as they appear to have been changed in the original data source. The code, [PyCitySchools Challenge](https://github.com/jinnabelle/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb), shows steps on how to determine and delete the altered math and reading grades of the Thomas High School ninth graders. The analysis looks at the student performance by school, and it looks at the difference in performance with the exclusion of the grades from the Thomas High School 9th graders.


## Resources
- Data Source: schools.csv, students_complete.csv
- Software: Python 3.7 (Pandas), Jupyter

## Results 
The analysis takes out the Thomas High School 9th graders from the total scores and school performance to avoid the inaccurate results from the school. In total, there were 461 students that had their scores nullified. With this, the results below shows how performance at the total, district, and school level is affected by the change.

* How is the district summary affected?
There difference between the summaries is minimal. This is likely due to the number of student scores taken out of the total population of students (461 out of the almost 40,000 students in the dataset).  The metrics affected by the change are percent of students passing individual subjects (math and reading) and passing overall. <br>
**Original District Summary**<br>
![Original District Summary](Resources/District Summary _original.png)<br>
**Updated District Summary**<br>
![Updated District Summary](Resources/District Summary _updated.png)<br>

* How is the school summary affected?
The school summary was affected, again, only by the percent of students passing the individual subjects and both subjects, as well as the average math and reading scores.The average math score for Thomas High School went down by the hundredth decimal point and the average reading score went up by the hundredth decimal point. <br>
**Original School Summary**<br>
![Original School Summary](Resources/School Summary _original.png)<br>
**Updated School Summary**<br>
![Updated School Summary](Resources/School Summary _updated.png)<br>


The differences are so minimal that in terms of performance relative to other schools, Thomas High School did not change its ranking based on overall % of students that passed. The images from the question below shows the side by side view of the top 5 schools from the original pull and the updated pull.

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The school summary was also not affected much. Thomas High School was still at the top 5 performing schools across the schools involved with minimal changes to its passing percent and average grades. <br>
**Original School Summary**<br>
![Original School Summary](Resources/Top Schools _original.png)<br>
**Updated School Summary**<br>
![Updated School Summary](Resources/Top Schools _updated.png)<br>

* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
  * The ninth grade scores are nullified given that the code takes out the reading and math scores of the Thomas High School ninth graders.
  **Updated Reading Scores by Grade**<br>
   ![Updated Reading Scores](Resources/Reading Scores by Grade.png)<br>
  **Updated Math Scores by Grade**<br>
   ![Updated Math Scores](Resources/Math Scores by Grade _updated.png)<br>
  
  * Scores by school spending
  
  * Scores by school size
  
  * Scores by school type
  


## Summary
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
