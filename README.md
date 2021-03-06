# School District Analysis Challenge

## How is the district summary affected?


### Original District Summary
- Average math score 79%, avgerage reading score 81.9%, % passing math 75%, % passing reading 86%, %overall passing 65%
![OG_DistrictSummary](https://github.com/vrod237/School_District_Analysis/blob/master/OriginalDistrictSummary.png)

### Revised District Summary
- Average math score 78.9%, avgerage reading score 81.9%, % passing math 74%, % passing reading 85%, %overall passing 64%
![Revised_District_Summary](https://github.com/vrod237/School_District_Analysis/blob/master/RevisedDistrictSummary.png)

- Not much change occurred in the district summary, changes were around +/- 1% after replacing all 9th grade scores from Thomas High School with NaN.
---

## How is the school summary affected?
### Original School Summary
![OG_School_Summary](https://github.com/vrod237/School_District_Analysis/blob/master/OriginalSchoolSummary.png)
### Revised School Summary
![Revised_School_Summary](https://github.com/vrod237/School_District_Analysis/blob/master/RevisedSchoolSummary.png)
    
- Not much changed in the average reading/math score for students from Thomas High School. However, as you can see in the images above, % Passing Math, % Passing Reading and % Overall Passing was drastically reduced.

## Recalculate the high- and low-performing schools.   
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

- Thomas High School is no longer a top 5(2nd best) school out of all schools, it is now ranked #8 in the district. Average scores remained nearly the same however the other scores changed, as you can see below.
- % Passing Math 93.27% reduced to 66.91%
- % Passing Reading 97.31% reduced to 69.66%
- % Overall Passing 90.95% reduced to 65.08%

## How does replacing the ninth-grade scores affect the following?
#### Math and Reading Scores by Grade 
- All other grades remained the same except for 9th graders from Thomas High School.  
- 9th Grade Math Scores 83.59%% reduced to NaN
- 9th Reading Scores 83.73 reduced to NaN
#### Scores by School Spending 
- Only numbers in the $630-644 range were affected. Average math score (78.5%) and average reading score (81.6%) remained the same, however the % passing math, % passing reading and % Overall Passing were reduced.
- % Passing Math 73% reduced to 67%
- % Passing Reading 84% reduced to 77%
- % Overall Passing 63% reduced to 56%
#### Scores by School Size
- Only medium sizes schools (1,000 - 2,000) were affected. Average score remained the same, 83.4% is the average math score and 83.9% is the average reading score.
- % Passing Math 94% reduced to 88%
- % Passing Reading 97% reduced to 91%
- % Overall Passing 91% reduced to 85%
#### Scores by School Type
- As Thomas High School is a Charter School, District Schools were not affected in any way by replacing the 9th grade scores from Thomas High School. Average Math (83.5%) and Reading (83.9%) scores remained the same.
- % Passing Math 94% was reduced to 90%
- % Passing Reading 97% was reduced to 93%
- % Overall Passing 90% was reduced to 90%
