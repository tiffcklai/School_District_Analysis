# School District Analysis Challenge with Pandas and Jupyter Notebook

## Resources 
Jupyter Notebook, Pandas Library, Python 3.7

School: [schools_complete.csv](Resources/schools_complete.csv)

Student: [students_complete.csv](Resources/students_complete.csv) 

Challenge Code: [PyCitySchools_Challenge.ipynb](PyCitySchools_Challenge.ipynb)

## Overview of the school district analysis 
The school district was notified of academic dishonesty in the math and reading grades for 9th graders at Thomas High School (THS). To uphold state-testing standards, the analysis was performed to see the full extent of the altered academic grades. The math and reading scores for 9th graders at THS were replaced with NaNs and the school district analysis was repeated to observe the changes on the overall analysis.

## Results 

### District Summary Analysis
The district summary was slightly affected with the removal of the altered academic grades. It is observed that in the Original District Analysis, each column: the average math score, percentage passing math, percentage passing reading, and overall passing percentage was lower by 0.1%-0.3% in in comparison with the New District Analysis.

Original District Analysis 
![Original District Analysis](https://github.com/tiffcklai/School_District_Analysis/blob/main/Resources/district_summary_old.png?raw=true)

New District Analysis 
![New District Analysis](https://github.com/tiffcklai/School_District_Analysis/blob/main/Resources/district_summary_new.png?raw=true)

### School Summary Analysis for THS
In the school summary analysis, it is clear that the removal of the 9th graders math and reading scores have some minor changes in the % Passing Math, % Passing Reading and % Overall Passing. In the original school summary, the % passing math was 93.3% in comparison with the new school summary with 93.2%. For the % passing reading, the original percentage for THS was 97.3% and the new percentage was 97.0%. For the % overall passing, the original percentage was 90.9% versus the new percentage of 90.6%.

Original School Summary: [school_summary_original](Resources/school_summary_old.png)
![Original_School_Summary](https://github.com/tiffcklai/School_District_Analysis/blob/main/Resources/school_summary_old.png?raw=true)

New School Summary: [school_summary_new](Resources/school_summary_new.png)
![New School Summary](https://github.com/tiffcklai/School_District_Analysis/blob/main/Resources/school_summary_new.png?raw=true)

### THS Math and Reading Scores 
Replacing the math and reading scores for THS 9th graders, made no effect on their performance for % Overall Passing scores. They are still in the top 5 schools, in second place after Carbera High School. The changes between the original and new columns for average math score, average reading score, % passing math, % passing reading and % overall passing all range from 0.1-0.3. 

Original Top 5 School Results: [school_summary_original](Resources/top_schools_old.png)
New Top 5 School Results: [school_summary_new](Resources/top_schools_new.png)

### Additional Analysis for the Extent of the Altered Grades 

For the replacement of the 9th grade scores, there is no affect on the math and reading scores by grade as these were calculated for each grade independently of one another. Therefore, by changing the scores for 1 grade, it does not affect the scores for another. 

The scores by school spending also did not have any affect with the altered scores from THS 9th graders. The average math and reading scores, and the % passing math and reading scores, and % overall passing had no change. 
Original spending per student results: [spending_per_student_original](Resources/spending_per_student_old.png)
New spending per student results: [spending_per_student_new](Resources/spending_per_student_new.png)

The scores by school size did not change with the removal of the 9th grade scores from THS. All of the columns (average math score, average reading score, % passing math, % passing reading, and % overall passing) exhibit the exact same values before and after the altered grades were replaced.
Original scores per school size: [scores_school_size_original](Resources/scores_school_size_old.png)
New scores per school size: [scores_school_size_new](Resources/scores_school_size_new.png)

Scores by school type exhibited no change from the replacement of the THS 9th graders scores. Both Chater and District school types continue to have the same scores and % passing for reading and math in the original and new analysis. 
Original scores by school type: [scores_school_type_original](Resources/scores_school_type_old.png)
New scores by school type: [scores_school_type_new](Resources/scores_school_type_new.png)

## Summary 

In conclusion, the removal of the 9th graders in Thomas High School had some impacts on the data set. In the school summary, it is observed that for THS, the percentage of students who passed math and reading were slightly lower when the altered grades were removed. Additionally, with the previous two percentages being lower, the overall passing percentage was also slightly lower. However, this does not affect their position in second place as one of the top 5 schools in the district. This analysis on the school summary was challenging as the removal of the 9th graders scores immediately invalidated the columns % passing math and % passing reading for THS. To accomodate this, it was corrected by only accounting for students scores in grade 10 to 12. Apart from the district summary analysis mentioned above and the school summary analysis, no other changes were found in the school analysis. This indicates that the extent of this altered data is not very drastic.



