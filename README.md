# Students-Performance-Analysis

![Alt text](https://github.com/Ogungbaigbe-Olaniyi/Students-Performance-Analysis/blob/main/download.jpg?raw=true)
## Project overview
- This Project analyzes students academic performance based on multiple factors such as study hours, health status, tuition, videogames usage, attendance, and stress level. The goal is to identify the top factors influencing exam scores. Dataset was obtained from kaggle.com 
## Tools used
- Microsoft excel (pivot tables, charts , Dashboard, Regression analysis, corellation analysis)
- Power BI ( Data modelling, visualization)
## Research Questions
- How many students are been tracked
- What is the highest and lowet score
- what is the average score
- How does stress and health status affect score outcome
- Do students with tuition score better
- Does attendance, daily work and self study affect students exam score
- Can performance be predicted by students behaviour
- who are the top 5 students
- Is there any relationship between self study and exam score?
- what are the top 3 factors inpacting students performance
## Analysis Steps
- Downloaded dataset was in csv format was extracted to an excel sheet and saved in xlsx format and saved as student performance
- Dataset range is converted to a table and the columns are reviewed by identifying the variables ( e.g exam score, self study health e.t.c)
- Checking of data type to know which were numeric, categorical and text
- Target variable was identify which is exam score
- Data cleaning was done to check for duplicates, inputation to check for missing value and correct data type
- Perform descriptive analysis by summarizing key metrics : average exam score, highest and lowest score and number of students
- Group by categories using pivot tables to show average score by health, stress level, daily work, age and tuition
- plot bar chart, columen chart using the pivot tables
- Run corellation and regression analysis to view matrix and regression model
- Build interactive dashboard using excel and power BIs
- These steps will help replicate the analysis and verify the findings
## Analysis Files included:
### Dataset in csv format and xlsx format
### Students performance dataset analyis in xlsx format

### 📊 Regression Statistics
| Statistic              | Value   |
|------------------------|---------|
| R-squared              | 0.9107  |
| Adjusted R-squared     | 0.8921  |
| F-statistic            | 48.9525 |
| F-statistic p-value    | 0.0000  |
| Number of observations | 30.0000 

### 📉 Regression Analysis Summary
| Predictor        | Coefficient | p-value | Statistically Significant? |
|------------------|-------------|---------|-----------------------------|
| **ATTENDANCE**   | +0.29       | 0.002   | ✅ Yes                      |
| **VIDEO GAMES**  | +4.47       | 0.135   | ❌ No                       |
| **TUTION**       | -4.53       | 0.213   | ❌ No                       |
| **SELF STUDY**   | +6.46       | 0.000   | ✅ Yes                      |
| **HEALTH (GOOD)**| +10.69      | 0.062   | ⚠️ Borderline               |

### Corellatiom matrix and heat map 
![correlation heatmap](https://github.com/Ogungbaigbe-Olaniyi/Students-Performance-Analysis/blob/main/Correlation%20heat%20map.PNG?raw=true)
### Power BI dashboard
![dashboard](https://github.com/Ogungbaigbe-Olaniyi/Students-Performance-Analysis/blob/main/dashboard.PNG?raw=true)
## Key Insights or Findings
- Regression analysis shows the model expain 91.1% of variation in exam score as can be seen in the R squared value and 89.2% for the number of predictors and indicated by the adjusted R squared
- The significant F shows the model is overall statistically relevant
- students with higher self study hours and attendance score better
- excessive video gaming negatively impacted performance as can be seen form the correlation aanalysis
- Stress level and health status has moderate efffect on scores
- Tuition has a slight negative coefficients in the regression model
## Conclusion
Conclusively, the top three factors impacting the student performamce are:
- Self study
- Attendance
- Video games
## Recommendation 
Based on the analysis result, the following are the recommendations which can mitigate the reasons for low performance / score
1. Encourage and emphasize more self study and regular attendance among the students
2. Advicing students to reduce video games time or stop games playing before exams
3. Intoduction of busrsary for indigent students or student with financial stress
4. Making lecture hours or period flexible to reduce stress
## Contact
**Ogungbaigbe Olaniyi Olusola**
email: solay2k8@yahoo.com
