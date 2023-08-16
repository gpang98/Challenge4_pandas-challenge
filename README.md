# Challenge4_pandas-challenge

The python codes used are primarily using pandas to manipulate the two csv input files which was merged.  The merged file is used for all the 
computation for the required statistics as outline.

The original starting script has been utilized and the mark down comments are preserved.
Each steps of the codes have been given some clarification on the intent of the codes and 
general heading describe the overall workflow to get the intended output.


Below are a short summary of the result as requested.

## Summarises the analysis
Based on the analysis performed using pandas, we can conclude the following:

1. Total of 15 schools studied with 39,170 total students from Year 9 to 12 and total spending was $24,649,428.
Average Math and Reading are 70.34% and 69.98% respectively.  Assuming a pass of >=50%, 86.08% and 84.4% of the students are able
to pass Reading and Math respectively.  72.81% students are able to pass both subjects.

2. The 5 top performing schools based on Percentage Overall Passing are Griffin HS (81.34%), Cabrera HS (80.79%), 
Bailey HS (80.08%), Wright HS (79.72%) and Rodgriquez HS(79.42%).

3. The 5 bottom performing schools based on Percentage Overall Passing are Hernandez HS (66.36%), Huang HS (66.71%),
Johnson HS (67.19%), Wilson HS (67.46%) and Ford HS (67.47%).

4. Schools average math scores from Year 9 to Year 12 are ranging from 68.3-75.5% score.  
The average score are somewhat constant with slight variation from Year 9 to Year 12 per school.

5. Schools average reading scores from Year 9 to Year 12 are ranging from 68.0-73.3% score.  
Wright HS showed consistent drop in average scores from Year 9 to 12.

6. Spending Ranges (Per Students) between $585-630 produced the best averall result for average maths score, reading score,
% Passing Maths, % Passing Reding and % Overal Passing.  Spending more than this range doesn't improve the scoring.
 
7. Smaller school size (<1000 total students) produced the best overall result for average maths score, reading score,
% Passing Maths, % Passing Reding and % Overal Passing.  Larger schools showed deterioration in all the scoring.

8. Independent schools consistently performed better than government schools in all the scoring result for average maths score, reading score,
% Passing Maths, % Passing Reding and % Overal Passing.


## Draws two correct conclusions or comparisons from the calculations:

First conclusion is a smaller school size (<1000 total students) is better than a large one (2000-5000 total students).  
This is probably because teacher-student ratio is higher and more personal attention can be provided to monitor student progress.

Second conclusion is independent schools are performing better than government schools in reading and maths score.  
It is not clear why this is so.  Normally, independent schools have better budget but our data suggest that $585-630 spending ranges (per student) 
produced the best overall result.  So, purely spending more money is not the cause.  It could be linked to the first conclusion of the smaller 
school size since independent schools tend to be selective and smaller in size compared to government school. 
This is confirmed by looking at the very first output table.  
Independent schools have 427 to 2283 total student while government schools have 2739 to 4876 total tudents.
