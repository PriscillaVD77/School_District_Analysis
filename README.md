# School_District_Analysis<br>

## Overview

Maria is the chief data scientist for a city school district and needs our help preparing standardized test data for analysis, reporting and presentation. This data will help to provide insight about performance trends and patterns, so they can make informed dicisions for the district going forward.
## Purpose
We will aggregate the data and showcase trends in school performance
## Results
### How is the district summary affected? <br>
#### Original Ditsrict Summary
![old_district_summary](Resources/old_district_summary_df.png)
<br>
#### Corrected District Summary
![new_district_summary](Resources/new_district_summary_df.png)
### How is the school summary affected? <br>
In comparing the changes in our district summaries we see the following changes: <br>
<br>
-Total students decreased by 461 students <br>
-Average Math Score decreased by .1 point <br>
-Percentage of students passing math decreased by .2 percent <br>
-Percentage of students passing reading decreased by .3 percent <br>
-Percentage of students passing reading and math overall decreased by .1 percent <br>
<br>
#### Original School Summary
![border](Resources/border.png)
![old_school_summary](Resources/old_school_summary.png)
<br>
#### Corrected School Summary
![new_school_summary](Resources/new_school_summary.png)
<br>
In comparing the changes in our district summaries we see the following changes:<br>
*for some of our data, some of the changes are less significant with change going out to the hundreds place <br>
<br>
-The average math scores for the school decreased by .07 points <br>
-The average reading scores for the school decreased by .05 points <br>
-The percent passing math decreased by 26.36% <br>
-The percent passing reading decreased by 27.65% <br>
-The percent passing overall decreased by 25.87% <br>
<br>
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? <br>
We were able to change the scores for this group using the following code: <br>
<br>
![Replace Values](Resources/replace_9th_nan.png)
<br>
Using this code we are able to replace the values for the ninth graders while still performing our mathematic functions. This makes the number of total students the same while there is less data to compute. This makes the scores significally lower for passing when compared to other schools becuase there are less scores for the total students. <br>
### How does replacing the ninth-grade scores affect the following: <br>
#### Math and reading scores by grade <br>
The code for replacing our math and reading scores by grade are shown below: <br>
<br>
![old math scores](Resources/old_math_by_grade.png)<br>
<br>
![new math scores](Resources/new_math_by_grade.png)<br>
<br>
![old reading scores](Resources/old_reading_by_grade.png)<br>
<br>
![new reading scores](Resources/new_reading_by_grade.png)<br>
The only significant change for each of the new dataframes is that for Thomas High School, 9th grade scores are now Nan. There is no affect on other grades.

#### Scores by school spending <br>
In comparing the difference in scores based on spending ranges we see the following changes: <br>
##### Original Scores by Spending Ranges
![old_score_by_spending](Resources/old_scores_by_school_spending.png)<br>
##### Original Scores by Spending Ranges
![new_score_by_spending](Resources/new_spending_summary.png) <br>
There are small changes in the third spending range $630-$644 because this is where Thomas High School lies <br>
<br>
-There is a .02 point decrease for average math scores <br>
-There is a .04 point decrease for average reading scores <br>
-There is a .02% decrease in percent passing math <br>
-There is a .08% decrease in percent passing reading <br>
-There is a .08% decrease in percent of students passing overall <br>

#### Original scores by school size <br>
In comparing the difference in scores based on school size we see the following changes: <br>
##### Original Scores by School Size
![old_score_by_size](Resources/old_score_by_size.png)<br>
##### Corrected Scores by School Size
![new_score_by_size](Resources/new_score_by_size.png) <br>
There are small changes in the third spending range $630-$644 because this is where Thomas High School lies <br>
<br>
-There is a .02 point decrease for average math scores <br>
-There is a .04 point decrease for average reading scores <br>
-There is a .02% decrease in percent passing math <br>
-There is a .08% decrease in percent passing reading <br>
-There is a .08% decrease in percent of students passing overall <br>
#### Original Scores by school type <br>
In comparing the difference in scores based on spending ranges we see the following changes: <br>
##### Original Scores by Schoo Type
![old_score_by_type](Resources/old_score_by_school_type.png)<br>
##### Corrected Scores by School Type
![new_score_by_type](Resources/new_score_by_school_type.png)<br>
There are small changes in the school type for charter schools because this is where Thomas High School lies <br>
<br>
-There is a .01% decrease for percent passing math <br>
-There is a .04% decrease for percent passing reading <br>
-There is a .04% decrease for overall passing <br>
## Summary 
As shown in our analysis above, the Thomas High School 9th grade scores had the biggest impact on the results for Thomas High school in the per_school_summary data frame. We saw dramatic decrease in their percent passing math with a decrease of 26.36%, the percent passing reading with a decrease of 27.65%, and the percent passing overall with a decrease of 25.87%. We also see major changes in the total district summary overall with percentage of students passing math decreased by .2% and
percentage of students passing reading decreased by .3%. We saw more changes through the analysis but they had little significance on the data set overall. The biggest impact on the scores were on the analysis on Thomas High School because the change in overall scores was not enough to have much impact on the districts scores. 
