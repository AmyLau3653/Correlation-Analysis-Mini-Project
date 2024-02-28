# Correlation-Analysis-Mini-Project
## What data do we have?
We received a data set from the survey given to students in CS105, CS111, and CS141. The survey consisted of personal preferences and facts for each student to answer. However, we focused on questions that were more relevant to our topic and analyzed them.  
## What would we like to know?
We would like to know what correlations there are between a student's music preferences and if they go to the gym. More specifically, we want to see if certain music genres are more heavily associated with those who have a specific workout, fitness goals, and how frequently/infrequently they go to the gym.  
## Exploratory Data Analysis
After making a subset dataframe of the class survey data set, we created visualizations for exploratory data analysis. Visualizations we created included various bar graphs, a heat map, a box plot, a pie chart, a violin plot, a stacked bar plot, and a spider chart. 
## Forming Hypotheses
There were 3 hypotheses we formed from our data:  
1. $H_0$: There is no correlation between music genre and going to the gym.  
2. $H_0$: There is no correlation between music genre and type of gym workout.  
3. $H_A$ : (Our Hypothesis) There is a correlation between between and individual's type of workout and whether they make a playlist.  
## Testing Hypotheses
We tested hypothesis #1 using Cramer's V, and tested hypotheses #2 and #3 using chi-square analysis.
## Conclusion
Based on Cramer's V and chi-square tests, none of the null hypothesis were rejected because the data was not statistically significant.
