# School District Analysis

## Project Overview
The school board has notified Maria and her supervisor that the student disctrict analysis file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Maria has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of teh data intact. Once I've replaced the math and reading scores, I will repeat the school district analysis to write up a report to describe how these changes affected the overall analysis. Here are the steps that I will have to take to complete this analysis.

1. Replace all the Thomas High School 9th Grade math and reading scores to NaNs.
2. Subtract these NaN scores from the overall math, reading and both percentages of the grades.
3. Compare the new percentages to the original percentages.
4. Compare the top 5 and bottom 5 performing schools from the new analysis with the old analysis.
5. Determine and describe the changes that occured by re-running the analysis.


## Resources
- Data Sources: schools_complete.csv, students_complete.csv
- Software: Python 3.6.1, Pandas Dataframe 1.3.4

## Summary
- Number of students and student grade totals:
    - There were 39,170 total students before any of the academic dishonesty analysis was run.
    - Of these 39,170 total students, 461 of them were in the 9th Grade of Thomas High School. 
    - After subracting the number of students that are in the 9th Grade of Thomas High School, the new total student count is 38,709.
- Math and Reading Scores Analysis for 9th Grade Thomas High School:
    - The original percentage passing for math was 93.272171%.
    - The percentage passing for math after the analysis was revised and run is 66.911315%.
    - The original percentage passing for reading was 97.308869%.
    - The percentage passing for reading after the analysis was revised and run is 69.663609%.
    - There is a very stark difference between the original math and reading scores pre and post academic dishonesty analysis.
    - However, these numbers really cannot paint a complete picture and be used as enough evidence to prove academic dishonesty. Other factors need to be taken into account which were not included in the dataset that was provided.
- Comparison of Top 5 and Bottom 5 performing schools: 
    - Before the academic dishonesty analysis was run, the Top 5 Performing Schools were:
        1. Cabrera High School
        2. Thomas High School
        3. Griffin High School
        4. Wilson High School
        5. Pena High School
    - Diana DeGette recieved 73.8% of the vote with a vote total of 272,892.
    - Raymon Anthony Doane recieved 3.1% of the vote with a vote total of 11,606.
- The winner of the election was:
    - Diana DeGette who received 73.8% of the vote with a vote total of 272,892.
 
 
