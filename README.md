# School District Analysis
The purpose of this analysis is to analyze school system data through the performance of the student body of numerous schools and how the performance of each school's student population performed through standardized testing. This analysis looks at whether or not funding and school type may correlate to the general performance of each school's student body population.

---

# Results
* # District Summary
The district summary table shows the overall summary for the entire district and does not give enough information to allow further explanation other than give a summary of the total number of schools, total number of students, average math and reading scores, etc. troughout the district. 

* # School Summary
In the school summary, it is noted that generally charter types have significantly better overall passing rates and have smaller populations. Throughout both school types, charter and district, there is a strong correlation that if there are more students attending "X" school, more funding is allocated to those schools. Although this correlation is true, it does not explain why when comparing district and charter school types with a population of more than a thousand and less than three thousand, district schools have significantly lower overall passing rates. A question arises within this portion regarding whether or not there is a difference in how schools allocate these funds or if there are more material or financial donations between school types. When viewing the per capita for each student, there is a strong correlation that the more funding a school receives, the more per capita per student. However when comparing school types, they appear to have similar trends--the more funding is received based on thier student population, the more capita per student however this does not explain why there is a signifcant overall passing rate difference.

* # Replacing Scores
Replacing ninth graders' math and reading scores with NaN for Thomas High School's performance has significantly lowered the overall passing rate by comparison to other schools of the same school type. Dismissing ninth graders' data generally decreased numerical values of: the average math and reading scores; scores based on school spending and school size (student population). However scores based on school type only for Thomas High School decreased as the remaining schools remain unchanged. 

---

# Summary
As stated before, replacing ninth graders' scores with NaN for Thomas High School decreased the overall passing rate, scores by school spending, and school size. Despite replacing ninth graders' scores with NaN, the scores for Thomas High School has decreased and only changed its position within top or bottom five schools. If ninth grade scores were not replaced, Thomas High School would be in the top five schools.
