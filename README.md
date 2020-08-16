# School_District_Analysis
I was tasked with examining data for a school district. The data included all students, schools, school type, reading and math scores, and budgets. I used this script to preform an analysis on the district to determine the top preforming schools, average math and reading grades, sort thru the data on a by grade level, and calculate the budget used per student. Part way thru my analysis I was informed one school had shown evidence of academic dishonesty with their 9th grade class and so code was added to change their scores to NaN. 
## Findings
![top_schools_original](https://user-images.githubusercontent.com/68392225/90340210-325ca700-dfbc-11ea-8ed2-8ec4b55d5aa5.png)

-Before the evidence of academic dishonesty was recieved, Thomas High School was #2 in the top 5 preforming high schools in the district. 

![top_schools_new](https://user-images.githubusercontent.com/68392225/90340371-4523ab80-dfbd-11ea-87e3-b5f272542ca4.png)

-After the evidence was presented Thomas High School fell out of the top five. 

-Overall, the academic dishonesty really only affected Thomas High Schools 9th grade, the top schools are all still charter schools and Thomas High School didn't even fall into the bottom 5 preforming school even with an entire grades scores as invalid!

![bottom_schools](https://user-images.githubusercontent.com/68392225/90340554-a26c2c80-dfbe-11ea-89fb-6b81fb69dbe2.png)
-The updated math and reading scores only affect the 9th grade level, with overall scores becoming slightly lower. 
![average_grade_original](https://user-images.githubusercontent.com/68392225/90341087-47d4cf80-dfc2-11ea-8070-07d57e121886.png)
![average_grade_new](https://user-images.githubusercontent.com/68392225/90341095-558a5500-dfc2-11ea-9b0f-a8f8d4d4283f.png)

-If we include all grades, the changed grades make almost no impact to the overall passing score, going from 90% passing to 87% passing.

-All the results are still higher than district schools.

## Conclusion 
The overall passing percentage of students was lowered slightly by the NaN scores from Thomas High School. Despite Thomas High School losing the scores of an entire grade, it was still preforming better than the district schools. Charter schools can outpreform district schools at almost all levels. District schools spend more money per student in a lot of cases, and are still outpreformed academically by charter schools. 
