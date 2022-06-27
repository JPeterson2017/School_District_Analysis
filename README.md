# School District Analysis
## Overview
The purpose of this project was to analyze student and school performances based on school budgets, size, and grade levels. After completeing the original code, it was discovered that there were descrepencies with the 9th Grade test scores at Thomas High School. The goal for the Challenge was for us to remove those descrepencies and evaluate the corrected values. 

## Results
* The district summary was only slightly affected by removing the inaccurate values. The percentage that passed reading and math slightly descreased. 
* After making changes to correct the values for Thomas High School, the school summary showed that the ...........
* Without the 9th grade scores, Thomas High School has a slightly lower pass rate, an increase in average reading scores, and a decrease in average math scores. 
* By replacing the ninth-graders scores from Thomas High School with NaN...
     - The average Math score for 9th grade, decreased from 83.418 to 83.350
     - For scores by school spending, the variable would have stayed the same.
     - The Scores by school size are no longer neccessarily all inclusive because although we are counting the 9th grade students from Thomas High School, we do not have their actual, correct test scores. 
     - Scores by school type for Charter were already very close to what the NaN values were previously, therefore, the average scores did not change much. 
     - PREVIOUS RESULTS WITH THOMAS HIGH SCHOOL, 9th GRADE SCORES:
     ![OriginalScores!](/Resources/Previous_School_Summary.png)
     - NEW RESULTS WITH THOMAS HIGH SCHOOL, 9th GRADE SCORES AS NaN:
     ![UpdatedResults](/Resources/Corrected_School_Summary.png)

## Summary
After replacing Thomas High School's 9th grade scores with NaN, the schools overall pass rate decreased from 90.94% to 90.63%. The average math score for the school, descreased from 83.418 to 83.350. The average reading score increased from 83.848 to 83.896. Although the average reading score increased, the pass % for reading decreased from 97.309% to 97.0187%.
