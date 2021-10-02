# School_District_Analysis<br>

## Overview

Maria is the cheif data scientist for a city school district and needs our help preparing standardized test data for analysis, reporting and presentation. This data will help to provide insight about performance trends and patterns, so they can make informed dicisions for the district going forward.
## Purpose
We will aggregate the data and showcase trends in school performance
## Results
### How is the district summary affected? <br>
#### Original Ditsrict Summary
![old_district_summary](Resources/old_district_summary_df.png)
<br>
#### Corrected District Summary
![new_district_summary](Resources/new_district_summary_df.png)
<br>
In comparing the changes in our district summaries we see the following changes: <br>
<br>
-Average Math Score Increased by .1 point <br>
-Percentage of students passing math increasded by .2 percent <br>
-Percentage of students passing reading decreased by .3 percent <br>
-Percentage of students passing reading and math overall decreased by .1 percent <br>
<br>
### How is the school summary affected? <br>
#### Original School Summary
![old_school_summary](Resources/old_school_summary.png)
<br>
#### Corrected School Summary
![new_school_summary](Resources/new_school_summary.png)
<br>
In comparing the changes in our district summaries we see the following changes:<br>
-There is little to no significant change. In order to see change numbers are format out to at least the hundreds place.
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? <br>
We were able to change the scores for this group using the following code: <br>
<br>
![Replace Valuesy](Resources/replace_9th_nan.png)
<br>
### How does replacing the ninth-grade scores affect the following: <br>
### Math and reading scores by grade <br>
#### Scores by school spending <br>
#### Scores by school size <br>
#### Scores by school type <br>
##Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
