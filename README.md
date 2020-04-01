# School_District_Analysis
Challenge:
Replace the reading and math scores for ninth graders at Thomas High School with NaN.

## How is the district summary affected?
- Negating the Thomas High School 9th graders/ reading scores lowered the district's average math score, passing math percentage, passing reading percentage and overall passing percentage. This indicates that Thomas High Schools' 9th graders performed higher than average compared to students of all grade levels within the district.

## How is the school summary affected?
The affect on Thomas High Schools' performance is mixed. While the average math score within the high school dropped by approximatley 0.07 points (from 83.42 to 83.35), average reading score increased by almost 0.06 points (from 83.85 to 83.90). This indicates that the 9th grade class did not perform as well in reading as the other grade levels at Thomas High School. Percentage passing in all categories (Math, Reading, and Overall) dropped significantly due to all their 9th graders having invalid scores.

## Recalculate the high- and low-performing schools. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
After clearing out the 9th grade class' scores, Thomas High School's ranking drops to 8th to last place, coming from second place in the district.

## Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type. How does replacing the ninth-grade scores affect the following?
### Math and Reading Scores by Grade
Only the 9th grade class' scores for math and reading are 'NaN'.

### Scores by School Spending
Thomas High School spends on average $638 per student and as such, changes to Thomas High School's data changes the data within the $630-644 spending range. We see that the negation of Thomas High School's 9th grade class scores does not affect the average math score and average reading score within the spending range (78.5 and 81.6, respectively). However, we do see a drop in passing percentages with math passing percentage dropping by roughly 6% (73% to 67%), reading passing percentage dropping by 7% (84% to 77%), and overall passing percentage by 7% (63% to 56%). This indicates that Thomas High School's 9th grade class had much higher passing rates than the schools within the spending range.

### Scores by School Size
In comparison to school of similar size to Thomas High School (Medium = 1000-2000 student population), the negation of the 9th grade class scores again did not change the average math and reading scores (83.4 and 83.9 respectively) indicating that the 9th graders scored about the same as the population within this group. The passing rates were affected in that all pass rate categories (math, reading, and overall) dropped 6% uniformly: math (94% to 88%), reading (97% to 91%), and overall (91% to 85%). 

### Scores by School Type
Thomas High School is a charter school within the district. When comparing the changes of charter school scores, the averages remained constant at 83.5 points for math and 83.9 points for reading. Math passing percentage dropped by 4% from 94% to 90%, reading passing percentage dropped 4% from 97% to 93%, and overall passing percentage dropped 3% from 90% to 87%. This indicates that Thomas High School 9th graders had a high passing rate percentage in math and reading.

## Conclusion
Overall the data could show the significance of the test taking performance of Thomas High School's 9th graders. The data currently indicates that they have a higher passing rate than most high schools in the district but not necessarily in test scores. It would be insteresting to see the average math and reading scores compare to district schools and charter schools and to see if there is a significant difference between how much money is spent per capita and testing outcomes.
