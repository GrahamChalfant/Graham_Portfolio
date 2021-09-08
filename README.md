# Graham Chalfant's Projects


---


## About Me
Hi! My name is Graham Chalfant, and I am interested in the intersection of data science and health. 

This repository records the data science projects I have completed for academic and self-learning purposes. I use RStuido for all of my projects and report them using RMarkdown. Along with R, I also know SQL, and I'm learning HTML.

Currently, I am writing my thesis for a master's degree in business analytics and creating a personal blog using [HUGO](https://gohugo.io/) and Github Pages. 

💼 [LinkedIn](https://www.linkedin.com/in/grahamchalfant97/)
📬 [GrahamChalfant@gmail.com](mailto:grahamchalfant@gmail.com)



---



### [Dissertation: The Power of @realDonalTrump](https://github.com/GrahamChalfant/Dissertation_Power_Of_realDonalTrump)

- Analyzed Trump's 16,000 presidential tweets to measure their influence on his approval ratings
- Calculated Trump's average daily Twitter sentiment using the dplyr package and a lexicon sentiment analysis approach 
- Used linear regressions to determine the strength of the connection between Trump's Twitter sentiment and approval ratings 

Below is a wordcloud of Trump's most frequently used positive and negative tweets. 
![](/images/wordcloud_trump_twitter_sentiment.png)



---




### [Stroke Prediction](https://github.com/GrahamChalfant/Stroke_Prediction)

- Built RF model with 98% accuracy using tuneRF() 
- Oversampled training set using ROSE package to account for data imbalance and low specificity 
- Correctly predicted 68% of actual strokes (specificity = 0.6829)



![](/images/stoke_by_age_and_gender.png)

Confusion matrix of RF model


| Prediction  | Yes         | No          | 
| ----------- | :---------: | :---------: | 
| Yes         | 28          |  2          | 
| No          | 13          |  1244       | 




---


### [Business Statistics Assessment](https://github.com/GrahamChalfant/Business_Statistics)

- Used Null Hypothesis Significant Testing and Estimation approach to measure the influence a marketing campaign had on grocery stores  
- The new marketing campaign (intrial) influenced grocery store's sales gain t(483.08) = -5.7173, P-value = 1.44e-08  

**95% confidence intervals for percent sales gain** of each store controlling for the outlet type, marketing campaign (intrial), and staff turnover.


![](/images/percent_sales_gain_controlling_for_outlettype_and_staff_turnover.png)


 
 ---



### [Database Design and R Shiny Dashboard](https://github.com/GrahamChalfant/Data_Management_Project)

#### Database Design

- Collaborated with a five-person, international team to engineer a SQL relational database from a business problem 
- Advised a DB design by producing an E-R diagram to identify entities, relationships, cardinalities, and attributes 
- Created logical design while adhering to 3NF and then physical design using SQL DDL 


Below is the ER diagram created for this project. 

![](/images/ER_diagram.png)

#### R Shiny Dashboard

- Generated R script to scrape XML API hygiene rating data from the UK Food Standard Agency
- Used the dplyr package to clean and format > 400,000 observations from Food Standard Agency 
- Visualized geolocation data, hygiene ratings, and business types using the packages mapdeck and ggplot2

![](/images/shiny_dash_final.png)



---



### [Social Determinates of Health](https://github.com/GrahamChalfant/Social_Determinants_Of_Health)

- Analyzed hospital records of inpatient samples to understand their healthcare costs and utilization
- Identified various relationships between patient demographics and costs, such as rising patient costs for men as they age 
- Utilized regression analysis to determine statistically significant relationships between variables (p-value < 0.05)

![](/images/average_cost_by_gender_and_age_group.png)



---
 
 
 
### [MLR Variable Selection Visulization](https://github.com/GrahamChalfant/Advanced_Data_Analysis_Project)

- Used MLR to determine the influence of each predictor variable on the outcome variable
- Found r-squared of each independent variable using loops
- Rearranged data using the dplyr package to arrange variables in order of r-squared
- Created MLR adding each independent variable, one at a time, based on r-squared in descending order using a loop
- Visualized MLR's adjusted r-squared by each variable added to determine the optimal number of variables 

**Adjusted r-squared per variable added to MLR.** The final model needed to consider two things: total adjusted r-squared and the principle of parsimony. From the below image, I felt that the optimal model contained all variables until "TotalHours." This model had an adjusted r-squared which was 1% less than the maximum but contained three fewer variables.

![](/images/multiple_lm_rsquared.png)

 
 
 ---
 
 
 
 
### [Customer Transaction Prediction Project](https://github.com/GrahamChalfant/Customer_Transaction_Prediction_Project)

- Found optimal ML models by testing different partition sizes, variables using information gain, and various sampling methods
- Defined best performing model using accuracy, recall, f-score, and precision
- Created cost matrices based on the business problem to estimate profit for each model in a high and low-cost scenario 

The graph below shows each model's accuracy, f-score, precision, and recall. 
![](/images/AIP_Model_Comparison.png)

The graph below shows the two cost scenarios, which were estimated based on annual mortgage payments in the UK. Profits would be mortgage payments received by the bank, and costs would be advertising costs. 
![](/images/AIP_Confusion_Matrix_Costs.png)

