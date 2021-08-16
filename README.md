# School_District_Analysis

# Overview of the School district analysis 
* The purpose of this analysis was to take data collected from seperate schools and analyze the students performance in reading and math scores. Based on the results we are able to see which students have earned a passing percentage in math and reading or both. Within the analysis, data surrounding funding for each student was also taken into consideration. Upon further examination it was discovered that there was potential cheating among 9th grade students at Thomas High school. Becuase of this these grades were removed and the analysis was done again without those points of data. Both Codes can be found within the notebook. 
## Results 

*   The district summary was affected slightly by removing the 9th grade student scores from the analysis. The result of removing these scores brought the reading and math scores down by about a precentage point. 
* How is the school summary affected?
* * while the number of total students in the analysis remained unchanged a new dataframe was created replacing empty scores with null values in order to keep an accurate analysis without ignoring the exsistance of 9th graders. This allowed the analysis to yeild accurate pass rates without ignoring the 9th graders. 
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* * by replacing the 9th grade scores the percent of students passing math and reading overall were significantly below other schools. by making the change Thomas high school went from 8th overall to 2nd overall passing. 
* How does replacing the ninth-grade scores affect the following:
* *  Math and reading scores by grade
* * * For the most part the math and reading scores are not affected with the exception of 9th grade reading and math scores which are replaced with NaN values. 
* * Scores by school spending
* * * the actual change to school spending is negligible with less than a percent change across the board. 
* * Scores by school size
* * * Because Thomas High school is a medium sized school it falls within the 1000-2000 student range. Similarly to the scores by school spending, the difference between including the 9th grade scores or not is too small to affect the outcomes after formatting the dataframe. 
* * Scores by school type
* * * Similarly to the other aspects of the analysis the changes to the actual percentages is next to zero.  
* Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
* * Within the analysis the percentages that were affected the most were the overall passing scores for math and reading. Without replacing the scores the scores were sitting around 60-70 percent. However after replacing the 9th grade scores those scores jumped to 90-97 percent respectively. the reason the change is so significant is because we are changing and targeting the entire population of the school. If these scores and practices were compared to all schools the changes would be much less noticeable. This was proven when the scores were actually compared and the scores changed by less than a percentage point. 
