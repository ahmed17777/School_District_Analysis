# School_District_Analysis

Syed Ahmed 
March 22, 2021 

## Project Overview 

In this project, I cleaned and analyzed School District data to fix any claims brought up regarding academic dishonesty regarding the reading and math grades for Thomas High School ninth graders. The following is a report of the process of cleaning and refactoring the code in Jupyter Notebook. 

## Results 
In this section I will be going over how each of the seven school district metrics were affected by changes in the data. 

1. How is the district summary affected?
> Upon examining the original PyCitySchools file and comparing it to the new one, there is no difference in the district summary. 

2. How is the school summary affected? 
> The overall passing for Thomas High School has decreased from 90.95% in PyCitySchools to 90.63%. 

3. How does replacing the ninth graders' math and reading scores affect Thomas High School’s performance relative to the other schools?
> Replacing ninth graders' math and reading scores affects Thomas High School's performance by fixing the illegitmately boosted overall passing percentage and math and reading scores that were previously reported. 

4. How does replacing the ninth-grade scores affect Math and reading scores by grade?
> By replacing the reading and math scores, the scores are replaced with NaN.

5. How does replacing the ninth-grade scores affect Scores by school spending?
> We observe a decrease in the overall percentage of students passing. 

6. How does replacing the ninth-grade scores affect Scores by school size?
> There is no significant change here. 

7. How does replacing the ninth-grade scores affect Scores by school type? 
> We can see that the percentage of overall passing students has gone down from 90% to 87%. 

## Conclusion 

After replacing the ninth graders' scores we found that the overall passing percentage for Thomas High school was illegitmately boosted, passing rate for Thomas High school has decreased by about 0.3%, we can see a decrease in overall percentage of students passing in scores by school spending, and a decrease in % overall passing by 3% in scores by school type. 
