# School_District_Analysis
# Overview
Our original analysis had us organize the student and school data to see if there was any correlation between budgets and student grades. 
After further review the school board has informed Maria that there were some academic dishonesty within the student_data file that was provided. 
Specifically the math and reading scores of the 9th grade class at Thomas High School needed to be removed. 
Maria has asked us the replace inaccurate data with NANs while keeping the rest of the data intact.

## Results

### How is the district summary affected?
    The district summary was not affected by the chnages in scores.
### How is the school summary affected?
    The over all passing % for Thomas High School dropped around 25% and the passing reading % dropped about 28% after the changes.
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    Thomas High School went from the second best performing school in overall passing % to the worst performing school by far.
### How does replacing the ninth-grade scores affect the following:
    Math and reading scores by grade
        There isn't any difference between the scores besides the 9th grade reading and math scores for Thomas High School showing NaN now.
        
    Scores by school spending
        The overall passing % dropped 7% in the $631-$645 school spending range (per student)
        
    Scores by school size
        The overall passing % and passing reading % both dropped 6% in the medium size schools category
        
    Scores by school type
        The district schools stayed the same however the charter schools Passing reading % and Overall passing % both dropped by 4% and 3% respectivley
## Conclusion
    After implementing the changes it did have some impact on the overall passing % and passing reading % for not only Thomas High school, but other charter 
    schools and schools in the same budget bucket as the Thomas High. Because of the incorrect numbers Thomas High School's results we very scewed and showed 
    them performing much better than they were. This could have major impacts on how the school district handles the budget in future years.
