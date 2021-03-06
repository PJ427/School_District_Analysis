# School_District_Analysis - PyCitySchool

  Upon completion of our origingal PyCitySchool Analysis, the school board found evidence of academic dishonesty concerning the math and reading grade for Thomas High School ninth grader.  Since the full extent of the academic dishonesty is unkown and the school board wants to uphold the state-testing standards they have requested a new analysis.  The new analaysis will replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.  Once completed we will repeat the orignal analysis with the new data.  

![](Resources/Replace_scores_with_NaN.PNG)

## Results: 

  o How is the district summary affected?
  
    - The removal of the Thomas High School, 9th Grade, math and reading scores had little to no impact on the original analysis.  However, it did have a considerable impac on Thomas High School reducing the original Overall Passing rate of 91% and to the new rate of 65%

![](Resources/changed_district_summary.PNG)
  
  o How is the school summary affected?  Thomas High School dropped from the 2nd ranked school to the 8th, though, it still ranked higher than any of the District schools

![](Resources/School%20Summary.PNG)

  o How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? Thomas High School saw a considerable drop in percentages passing math and reading as well as their overall pass rate.  They went from the 2nd ranked school overall to the 8th ranked school.
  
  o How does replacing the ninth-grade scores affect the following:
  
    - Math and reading scores by grade:  Setting 9th Graders scores to "NaN" did not significantly affect the overall scores.
  
    - Scores by school spending:  Thomas High School lower scores causes a reduction in the budget
  
    - Scores by school size: Removing the 9th graders saw roughly a 5% drop in each of their scores 
  
    - Scores by school type: Thomas High School which faired worse than the rest of the charter schools was still higher than any of the district schools

![](Resources/Scores_by_school_type.PNG)

## Summary

  o Four major changes in the updated analysis:
  
    1. School Rankings Changed
    2. Overall scores dropped
    3. Reduced Budget
    4. District Schools had no change
