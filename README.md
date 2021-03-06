# Statistics for Efficient Marketing Campaign in R
In this project we have used a marketing campaign dataset which consists of Segments of customers, the number of orders they placed and the number of different products they bought. Our study aims to find insights between these variables and inferences for better marketing. 
The entire project has been done on R Studio, the PDF files are knitted R Markdown files.<br>
<b>Project.md and Project.pdf are the files that contain the hypothesis. Data Exploration and Additional work are files we can refer to start off and a few insights.</b>

<br>
We use the terms Q to refer a Quantitative variable and C to refer a Categorical variable.
<ol>Our approach consists of 3 hypothesis:</ol>

## First Hypothesis: t-test
<ol>The first hypothesis involves testing whether Number of Web Orders(Q) placed by customers of different marital status(C) is different to focus advertising on a particular group and we found that mean of web orders placed by different marital groups is same[Parametric].
We also performed a second test to see which age group consumes more amount of wine and found out that customers whose age is above 45 consume more wine than whose age is below 45[Non-Parametric]. </ol>

## Second Hypothesis: Chi-square test of independence
 <ol>Second hypothesis tests to see if the number of children(C) a customer has and amount of sweet products(C) he/she purchases is dependent, and we found that these two variables are actually dependent on each other. </ol>
 
 ## Thrid Hypothesis: Linear Regression and Multiple linear regression
<ol>Lastly, the third hypothesis is to check if amount of wines purchased and age are linearly related. Further we do a linear regression between to predict amount of wines purchased from meat purchases, multiple regression between amount of wines purchased and kidHome and educational status.</ol>
<ol>We then perform boot strapping approach on the same multiple regression equation and also an additional model which could be predictors to wines purchased. As additional work, we have included Model fitting using AIC values(forward,backward and stepwise) and some exploratory data analysis.</ol>
<br>
Dataset has been taken from here: https://www.kaggle.com/rodsaldanha/arketing-campaign
