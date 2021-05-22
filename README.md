# School District Analysis with Pandas

## Overview

Since reading and math scores for ninth graders at Thomas High School appeared to have been tampered with due to academic dishonesty, the school board requested that NaN be used to replace Thomas's math and reading scores, while keeping other data intact. Also, the district's analysis needs to be reanalyzed because of changes in math and reading scores.

## Results

### District Summary
![district_summary](https://user-images.githubusercontent.com/82549782/119211636-6308ca00-ba81-11eb-9164-0b561ecc9ce6.png)
- From the graph above, we can see that the percentage of passing Math, Reading and the percentage overall passing after replacing scores are slightly lower than the data before replacing scores.

### School Summary
![school_summary](https://user-images.githubusercontent.com/82549782/119211784-34d7ba00-ba82-11eb-806b-8f97fc3665c4.png)
- Thomas High School's percentage of scores and percentage overall passing rate are about the same before and after replacing scores. 

![top_school](https://user-images.githubusercontent.com/82549782/119215103-93f4f900-ba99-11eb-89fa-4822d21a31dd.png)
- Replacing the ninth graders' math and reading scores does not affect Thomas High School's performance a lot. 
- Based on the overall passing rate, Thomas High School ranked at the second place no matter the scores are replaced or not. 

### Math and Reading Scores by Grade
![math_reading_scores_by_grade](https://user-images.githubusercontent.com/82549782/119211938-47062800-ba83-11eb-9664-b1289abf9f72.png)
- Only ninth-grade scores in Thomas High School are replaced with NaNs, other scores remain the same.

### Scores by School Spending
![scores_by_spending](https://user-images.githubusercontent.com/82549782/119215030-1204d000-ba99-11eb-9d9c-54003436f52e.png)
- Replacing the ninth-grade scores does not affect the Scores by School Spending.
- The higher the school spending range per student, the lower the average scores. 

### Scores by School Size
![size_summary_without_NaNs](https://user-images.githubusercontent.com/82549782/119215321-f8fd1e80-ba9a-11eb-81eb-a77cb9918126.png)
- Replacing the ninth-grade scores does not affect the Scores by School Size.
- The schools with the largest number of students had the lowest average scores This may be because there are too many students in one class and it is difficult for one teacher to manage so many students. Therefore, the best school size is 1000 ~ 2000.

### Scores by School Type
![type_summary_without_NaNs](https://user-images.githubusercontent.com/82549782/119215551-62316180-ba9c-11eb-90c5-679c1fadb341.png)
- Replacing the ninth-grade scores does not affect the Scores by School Type.
- Charter school has a higher average scores.

## Summary 
Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are:
- Average Math Score decrease from 79.0 to 78.9.
- Percentage of Passing Math decrease from 75% to 74.8%.
- Percentage of Passing Reading decrease from 86% to 85.7%.
- Overall Passing Rate decrease from 65% to 64.9%.
- The reason the score averages and percentages didn't change much after the replacement is that we removed both Thomas's ninth-graders' scores and numbers.
