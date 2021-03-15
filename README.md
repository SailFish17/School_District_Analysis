# School_District_Analysis

## Overview of the District Analysis

The purpose of this analysis was to prepare the results of standardized math and reading tests for a city school district so that the results of these tests could be viewed against a variety of variables; school, grade, school type (district vs. chartered), school size, and school and per capita budget.  In the midst of the analysis, it came to the attention of the Board of Education that one high school may have had some issues with a subset of their data due to academic dishonesty.  To reframe the analysis, the 9th grade reading and math scores of Thomas High School needed to be removed from the original analysis and the analysis redone.


# Results: 
### Initial Review 

In the orignal analysis in the module we reviewed 5 metrics for each high school:
  - Average Math score
  - Percentage passing math at a grade score of 70 or higher
  - Average Reading score
  - Percentage passing reading at a grade score of 70 or higher
  - Overall percentage passing both reading and math, that is, where a student scored both math and reading at a grade of 70 or better.
  
These metrics were maintained for all subsequent analysis work carried out.
  

### The District Analysis
The origninal district summary returned the following metrics:
  - 79.0 = Average Math Score
  - 75%  = Percentage passing math at a grade score of 70 or higher
  - 81.9 = Average Reading score
  - 86%  = Percentage passing reading at a grade score of 70 or higher
  - 65%  = Overall percentage passing both reading and math


When the data was rerun after the removal of the suspect 9th grade data at Thomas High School the following changes were seen in the metrics:
  - 78.9 = Average Math Score
  - 74.8%  = Percentage passing math at a grade score of 70 or higher
  - 81.9 = Average Reading score
  - 85.7%  = Percentage passing reading at a grade score of 70 or higher
  - 64.9%  = Overall percentage passing both reading and math

There was no difference in the reading scores.  The average math score did drop and this led to a subsequent reduction in the overal passing percentage.

### How is the school summary affected:

 - The school summary was affected as shown by the data.  Reductions in the average math, average reading, % passing math, %passing reading, and % overall passing for Thomas High School are clearly evident.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools:

 - Prior to replacement of the 9th grade data for Thomas High School, the school showed and excellent 91% overall passing percentage. 
 - After the suspect data was replaced with null values, the overall passing percentage decreased to 65%.

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade:
- The math and reading scores by grade were replaced with NaNs or null values.
 
#### Scores by school spending:
- Scores by School Spending changed at the $630-644 range: the percentage passing math dropped from 73.48% to 73.46% - percentage passing reading dropped from 84.39% to 84.31% - overall passing percentage dropped from 62.85% to 62.77%
 
#### Scores by school size:
- Scores by School Size did not change. It remained the same. 

#### Scores by school type:
- Scores by School Type did not change. It remained the same.

## Summary

The four major changes in the updated school analysis:

- The math and reading scores were replaced with NaNs that change the dataframes.
- Scores by school spending had dropped but with no significant change.
- We can clearly see the changes did not effect school size and school type.
- The district summary was affected the most.
