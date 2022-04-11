# School_District_Analysis
## Overview
---
#### The purpose of this challenge was to analyze school performaces in a certain district. The analyzed data included the type of school (charter or district), the total amount of students at each school, the budget of the school, grade level, math scores of each student, reading scores of each student, and overall passing rate of the students at the school. Because of a data integrity issue, the module results had to be re-configured for the challenge.
---
## Results

#### Thomas High School
##### While analyzing the module data for the schools, the school board identified academic dishonesty amongst the ninth graders at Thomas High School. In order to uphold state-testing standards, the board decided to exlcude any math or reading testing scores from the ninth graders at Thomas High School. Those students scores have been replaced with the value NaN.

#### The district summary
##### The district summary included the total data from all 39,170 students across all 15 schools in the district. Included are the average math score/percentage, average reading score/percentage, and overall passing percentage for both math and reading. The overall passing percentage of the district is 64.9%. This data only differs slightly by .3% from our orignal module analysis, 65.2%, which included the 9th graders from Thomas High School.
##### Refactored District Summary:
![](https://github.com/yfaulkne/School_District_Analysis/blob/main/Resources/District_Summary_No_Thonas.PNG)

#### The school summary
##### The school summary included all of the data from the district summary grouped by school. As seen in the two snapshots below, Thomas High School performance suffered by only a little as compared to the original data that included the 9th grade data.
##### Original:
![](https://github.com/yfaulkne/School_District_Analysis/blob/main/Resources/School_Summary_Original.PNG)
##### Refactored:
![](https://github.com/yfaulkne/School_District_Analysis/blob/main/Resources/School_Summary_no_Thomas.PNG)

#### The top 5 and bottom 5 performing schools, based on the overall passing rate
##### The top 5 and bottom 5 performing performing schools did not change after removing ninth graders from the data. Although the 9th grade scores were excluded, Thomas High School still performed in the top five of all schools.
##### Top 5:
![](https://github.com/yfaulkne/School_District_Analysis/blob/main/Resources/Top_5_Schools.PNG)
##### Bottom 5:
![](https://github.com/yfaulkne/School_District_Analysis/blob/main/Resources/Bottom_5_Schools.PNG)

#### The average math score for each grade level from each school
##### Thomas High School 9th grade students have a NaN value represented in the dataframe for Math Scores due to the data being removed from the anaylsis.
![](https://github.com/yfaulkne/School_District_Analysis/blob/main/Resources/Math_Scored_by_Grade.PNG)
#### The average reading score for each grade level from each school
##### Thomas High School 9th grade students have a NaN value represented in the dataframe for Reading Scores due to the data being removed from the anaylsis.
![](https://github.com/yfaulkne/School_District_Analysis/blob/main/Resources/Reading_Scores_by_Grade.PNG)
#### Scores by school spending per student, by school size, and by school type
##### The scores by school spending per student did not differ between the original data and the data excluding Thomas High School 9th graders.
##### The scores by school size did not differ between the original data and the data excluding Thomas High School 9th graders.
##### The scores by school type did not differ between the original data and the data excluding Thomas High School 9th graders.
![]()
![]()
![]()
---
## Summary
#### The results above show that the testing scores from the 9th grader students at Thomas High School skewed the data by a small margin. This may not have been as obvious if the dataframe for the school data summary had been formatted to one decimal place or no decimal at all. In a dataset such as this, every percentage point counts when it comes to comparing and contrasting to other schools. The data could have been altered more heavily if the school population of Thomas High hadn't been re-calculated to exclude the 9th graders for the challenge. Both reading and math scores for Thomas are slightly different as well as the percentages for math and reading due to the altered number of students represented in the data.
