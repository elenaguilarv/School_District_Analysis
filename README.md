# School_District_Analysis
Using Python and pandas Library

This analysis looks at the math and reading scores of students from 15 different city high schools. The high schools are analyzed based on what type of school they are, their budget, their size by student population, and more. This analysis can support administrators in making decisions to help improve student test scores and can allow them understand if school budgets and allocations have an impact or influence on students' scores.

## Challenge Questions
Scenario: The score averages of the ninth graders at Thomas High School are incorrect and have been removed and changed to show "NaN" instead. Below is a review of how these changes in the data have changed the overall PyCitySchools Analysis.

- The district and school summary DataFrames are recreated.

How is the district summary affected?

The district summary is not affected by the update. The total number of students remain the same and so does the total budget for all the schools. The average math and reading scores do change but not enough to change the number when rounding to two significant figures.

How is the school summary affected?

The school summary is also not affected by the data updates.

- The high- and low-performing schools are recalculated.

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

Prior to replacing the ninth graders' scores from Thomas High School, they were the second top performing school right behind Cabrera High and in front of Griffin High. Once the reading and math scores were updated, Thomas High School got moved out of the top five but was not affected enough to move into the bottom five performing schools. Those remained the same. 

- How does replacing the ninth-grade scores affect the following:

Math and Reading Scores by Grade?

The average math and reading scores of the 9th graders at Thomas changed from 83.6 and 83.7 respectively, to NaN. All other scores remained the same.

Scores by School Spending?

The spending bin of $630-644, the one Thomas High School is in was affected by the changes. Their percentage passing math, reading, and overall, decreased.

Scores by School Size?
The medium school size category (1000-2000) where Thomas High School lies showed a decrease in the percentages of those passing math, reading, and overall. 

Scores by School Type? 

Since Thomas High is a Charter school the updated scores on the 9th graders did affect the Charter schools' average math and reading scores along with the math, reading and overall passing percentage. 
