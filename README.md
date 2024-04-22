# Jamboree 
has helped thousands of students make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort. They want to launch a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

## Problem Statement:
1. To understand what factors are important in graduate admissions and how these factors are interrelated among themselves 
2. To predict chances of admission to Ivy League Schools, given the rest of the variables


## Steps Performed:  [Link to Code](https://github.com/madhavchekka/Regression/blob/main/Project%20Jamboree%20-%20Linear%20Regression.ipynb) 
1. Data Pre-processing
2. Exploratory Data Analysis
3. Inferential Statistics
4. Univatiate, Bivariate, and Multivariate Analysis
5. Splitting the data into train & test sets
6. Training Linear Regression Models - Linear Regression - Ordinary Least Squares, Ridge, Lasso, Weighted Least Squares
7. Testing Linear Regression Assumptions





### Final Insights:

1. CGPA, GRE Score, TOEFL Score have a very high correlation with Chance of Admit. Same can be inferred from the weights of the Linear Regression model as well
2. GRE Score, TOEFL Score are very highly correlated with CGPA 
3. Math Aptitude & English skills of students from higher rated universities seem to be better 
4. Students from university with higher rating, have better chances of admission into Ivy schools
5. Using Linear Regression with/without regularization, best perfomed model has an r2score of 0.83 -- improvement is required 


###  Inferences: 
1. Median GRE score, TOEFL Score, CGPA, LOR, SOP of students from universities with university ratings are different 
2. University rating & Research are associated. 
3. Students with research experience has higher median/mean CGPA, GRE Score, and TOEFL Scores. Their median chances of admission is also higher than that of students without experience


### Recommendations:

1. Recommend collecting more datapoints and balanced data to have more/better data for training
2. Collecting more datapoints like Years of work experience, Current Discipline, Targeted discipline at the Ivy School, Research papers published, IELTS Score, and others would help improve the model predictions
3. Recommend using different ML Models like Decision Trees to predict the Chances of admission - to improve model

### Potential Business Benefits:
1. Targeted ads for students with less/mediocre chances of admission into Ivy League. To enroll into Jamboree to improve GMAT/GRE/SAT Scores and increase their admission chances
2. As the model gets improved, it gives competitive edge to Jamboree over the competition and leads to more website traffic & enrollments 
