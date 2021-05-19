# School_District_Analysis

## Project Overview
Maria has assigned me the task of re-evaluating the district grade data in light of Thomas High School being flagged for academic dishonesty with respect to its ninth graders.  To that end, I have modified the data to exclude 9th grade testing results from Thomas High School, performed analysis on the revised data set, and compared that against the original to measure the extent of the differences between the two, so as to determine the severity of the academic dishonesty.

## Resources
- Data Sources: clean_students_complete.csv, missing_grades.csv, schools_complete.csv, students_complete.csv
- Software: Python 3.9.4 via Anaconda Jupyter Notebook

## Results
The analysis of the grade data showed that:
- The district summary showed small negative changes overall after controlling against the tainted results, with a negative adjustment of 0.1 points in the math score (78.9 vs. 79.0), no change in the reading score, a 0.2% negative adjustment in the passing percentage for math (74.8% vs. 75.0%), a 0.1% negative adjustment in the passing percentage for reading (85.7% vs. 85.8%), and a 0.3% negative adjustment in overall passing percentage (64.9% vs. 65.2%).
- The school summary showed no statistical change in the average math score for Thomas High School within one decimal point, still at 83.4.  A measurable decrease was observed with respect to its average reading score, being assessed at 83.9 from the previous score of 83.8, however minute.  For the percentage of passing students, the passing rate for math was negatively adjusted to 93.2% from 93.3%, for reading it was also negative, to 97.0% from 97.3%, and for both subjects, the change was negative as well, decreasing to 90.6% from 90.9%.
- The performance of Thomas High School relative to other schools was unchanged relative to the passing rate for math after adjustments against its math scores were made, but slipped two spots below Griffin High School and Cabrera High School in terms of reading scores, and just like with the passing rate for math, Thomas High School's performane rankings for the overall passing rate was left unchanged.
- Math and reading scores by grade within the 9th grade were affected by a 0.2 point drop to 80.1 from 80.3 for math scores, and a 0.1 point drop to 82.4 from 82.5 for reading scores.
- Scores by school spending were of no statistical effect within one decimal point.
- Scores by school size were of no statistical effect within one decimal point.
- Scores by school type were of no statistical effect within one decimal point.

## Challenge Summary
After analyzing the results, I have determined that the effects of the academic dishonesty from Thomas High School with respect to its ninth graders, within Thomas High School itself, within 9th grade overall, or within all high school grades in the entire district to not be statistically significant.  However, the one exception lies in relative performance withing reading performance, as Thomas High School moved two ranks ahead of Griffin High School and Cabrera High School with its tainted 9th grade reading scores, although math and overall passing ranks remain unchanged.  In that case, appropriate action against Thomas High School must be considered.
