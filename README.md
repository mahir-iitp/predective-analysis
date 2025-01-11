# predective-analysis
<h2>About</h2>
<pr>This project involves analyzing the relationship between students' Cumulative Grade Point Average (CGPA) and their placement packages (in lakhs per annum) using linear regression techniques. The dataset comprises 200 observations with the following variables:

CGPA: Students' cumulative grade point average.
Package: Placement package offered to the student (in lakhs per annum).
Objective: To develop a predictive model that estimates the placement package based on a student's CGPA.</pr>
<h3>Findings <h3>
<pr>The initial simple linear regression model, using CGPA as the sole predictor, yielded an R² score of approximately 0.781, indicating that about 78.1% of the variance in placement packages can be explained by CGPA. </br>

Introducing the random feature did not significantly improve the model's performance, suggesting it lacks predictive power.</br>

Adding the simulated IQ feature resulted in a slight improvement in the R² score to approximately 0.800, indicating a marginal increase in explanatory power.</pr>
<h3>Conclusion</h3>
<pr>The analysis demonstrates a positive linear relationship between CGPA and placement packages, with higher CGPAs generally associated with higher packages. While additional features like IQ may offer slight improvements, CGPA remains a strong predictor of placement outcomes. Future work could involve collecting more relevant features to enhance the model's predictive accuracy.</pr>
