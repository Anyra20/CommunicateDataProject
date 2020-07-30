# PISA 2012 Data Exploration
## by Maryna Misyura

## Dataset

> This dataset is a PISA 2012 survey of students' skills and knowledge in mathematics, reading and science. Also background information about 15-year-old students was collected in addition to test results. There are 485490 students in the dataset from 68 different countries.


## Summary of Findings

> In the exploration, I was interested in finding out what features are best in predicting the math, reading and science test results. I looked at many variables and relation between them:
- All three subject test scores are highly correlated with one another, which tell us the students rarely choose only one subject and neglect others
- Correlation between Social_economic status and test results is around 0.4. Students who have more economical, educational resources and support at home tend to get higher scores
- Amount of time students spend on subjects at school has very small influence on test scores
- East Asian countries: China-Shanghai, Singapore, Hong Kong-China, Japan, Korea have the highest average test scores in all subjects. 
- On average all subject's test scores increases with grade, but it is interesting that 10th graders slightly outperform 11th graders in all subjects
- On average across  all countries that participated in PISA 2012, boys outperformed girls by 11 score points in mathematics, but girls significantly outperformed boys in reading – by 45 score points. In science - there is almost no gap on average across all countries
- Homework_hour has weak correlation with test scores (around 0.25)
- On average girls spend 1 hour more on homework than boys. Also girls are more likely to spend more than 5 hours a week on homework than boys
- It's interesting to see that in the Top 1 performing country in all subjects - China-Shanghai - students have the biggest amount of homework on average - almost 14 hours a week. And Singapore is close by with more than 8 hours a week. At the same time in Korea (5th in list of most performing countries) students have the smallest amount of homework - around 3 hours a week.
- Correlation between Socio economic status of a student and test scores is pretty big - around 0.4.
- Level 2 on the PISA mathematics scale can be considered a baseline level of proficiency needed in life. Students who didn't reach Level 2 on math  scale disproportionately come from socio-economically disadvantaged families. More than half students from the first quarter of Socio_economic_status perform below this baseline proficiency level.
- On average boys feel better about math than girls, boys are more interested in math (57% boys vs 47% girls), less anxious about it (57% boys vs 67% girls) and believe themselves competent more (56% boys vs 43% girls). Also girls are less likely than boys to be among the highest-achieving students in mathematics.
- Math anxiety is negatively correlated with Math_self_concept (person's believes about his\her abilities in math)
- Math anxiety is negatively correlated not only with math test score, but also with reading and science scores
- There is correlation 0.6 between person's Math_interst and Math_self_concept(beliefs in being good at math)
- On average parents of girls and boys have similar beliefs and attitudes toward math. Most parents believe that math is important and encourage students of both genders to study math.
- Also these variables (Parents_math_important, Parents_math_for_career, Parents_like_math) are part of the Math_motivation variable and there is no significant correlation with math performance.
-What is interesting is that there are several countries in which the gender gap is reversed. Girls perform better in math than boys most noticeable in these counties Jordan, Qatar, Thailand, Malaysia, United Arab Emirates, Singapore
There also are several countries in which there is no significant gender gap.

- I worked more on the relationship between socio-economic status and students' performance at school. I looked at this relationship within individual counties. In some countries (Macao-China, Qatar) correlation between socio-economic status and math performance is quite low (around 0.2) and in some like Chily it's almost 0.6. 
- Then I looked at how disadvantaged students are distributed across schools within countries. I found out that on average correlation between Math performance of a school and socio-economic profile of schools (0.65) across all countries is higher than correlation between Math performance of students and their socio-economic status(0.4). Which means that disadvantaged students are gathered together at some schools, it can be rural schools or city schools like in the USA. 
-And then to compare different counties I looked at  how correlation between Math performance of a school and socio-economic profile of schools is in each country. Some countries are very segregated. For example, in Connecticut (USA) correlation coefficient between Math performance of a school and socio-economic profile of school is 0.895.


## Key Insights for Presentation

For the presentation, I wanted to look at how students' beliefs, attitudes and anxieties toward mathematics are related to math performance and gender of students.
- At first, I looked at distribution test scores by Gender. Across all countries that participated in PISA 2012, on average boys outperformed girls by 11 score points in mathematics. 
- Then I investigated several indexes which describe a student's beliefs and attitude toward mathematics. On average boys feel better about math than girls, boys are more interested in math (57% boys vs 47% girls), less anxious about it (57% boys vs 67% girls) and believe themselves competent more (56% boys vs 43% girls). Also girls are less likely than boys to be among the highest-achieving students in mathematics.
-Next, I looked at the relationship between math performance and Index of Math anxiety. I found out that there is a negative correlation(r = -0.36) between them across all countries. Then, I calculated averages of all countries and plotted them using regplot. Negative correlation appeared between averages of both variables for each country.
- There is also weak correlation between math self-concept and math performance.
- I decided to look at the differences between the math performance of girls and boys in each country. I calculated and plotted the math gender gap for each country.
- I found out that there are countries where girls actually outperform boys in math. These countries are: Jordan, Qatar, Thailand, Malaysia, United Arab Emirates, Singapore There also are several countries in which there is no significant gender gap.
-Next I wanted to know what are the differences between math anxiety levels and math self-concept for girls and boys from different countries. So I plotted Math_anxiety and Math_self_concept gender gap for each country.
- I noticed that countries with reversed Math gender gap also had very small or reversed differences in Math_anxiety and Math_self_concept gender gap. I used scatter plot to look for correlation.
-I found out that there is a negative correlation(-0.53) between math performance gender gap and math anxiety gender gap. The smaller their difference between average anxiety levels of girls and boys, the smaller their difference between average math performance of girls and boys.
Correlation between math performance gender gap and math self-concept gender gap is smaller (0.49). More girls believe they are good at math, the smaller is the average math performance difference between genders.

