# School District Analysis

### Overview
This Analysis of data from a school district was processed to examine the possibility of falsified testing scores at one of the schools in this district, Thomas High School. To do so, I replaced the questionable scores with a placeholder that allowed me to recalculate and compare the analysis without the numbers being affected by those values. 

### Results
- As you can see, the differences between district summaries is minimal. Without the data from the Thomas High 9th graders, the difference in the averages of overall test scores is less than 1%.
  - Before:
    - ![Data with Thomas High Freshmen](Resources/final-df-before1.png)
  - After
    - ![Data without Thomas High Freshmen](Resources/final-df-after1.png)
- The school summary, however, shows a more telling story.
  - ![Thomas High School summary without 9th Graders](Resources/th-summary)
- Clearly visible here is the evidence that replacing the ninth graders' scores made a negligible difference to the overall comparative ranking of Thomas High with other schools in the district.
  - Before:
    - ![Data with Thomas High Freshmen](Resources/top-schools-before.png)
  - After:
    - ![Data without Thomas High Freshmen](Resources/top-schools-after.png)
- How does replacing the ninth-grade scores has prompted the following results:
  - ![Scores by school spending](Resources/)
  - ![Scores by school size](Resources/)
  - ![Scores by school type](Resources/)

### Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
