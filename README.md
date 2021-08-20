# Graham Chalfant's Projects

## About Me


---



### [Dissertation: The Power of @realDonalTrump](https://github.com/GrahamChalfant/Dissertation_Power_Of_realDonalTrump)

- Analyzed Trump's 16,000 presidential tweets to measure their influence on his approval ratings
- Calculated Trump's average daily Twitter sentiment using dplyr and a lexicon sentiment analysis approach 
- Used linear regressions to determine the strength of the connection between Trump's Twitter sentiment and approval ratings 

Below is a wordcloud of Trump's most frequently used positive and negative tweets. 
![](/images/wordcloud_trump_twitter_sentiment.png)



---



### [Social Determinates of Health](https://github.com/GrahamChalfant/Social_Determinants_Of_Health)

- Analyzed patient hospital records of inpatient samples to understand costs and their utilization 
- Discovered various patient demographic and cost relationships, including average patient costs increase with age for males  
- Utilized regression analysis to determine statistically significant relationships between variables (p-value < 0.05)

![](/images/average_cost_by_gender_and_age_group.png)



---



### [Stroke Prediction](https://github.com/GrahamChalfant/Stroke_Prediction)

- Built RF model with 98% accuracy using tuneRF() 
- Correctly predicted 68% of actual strokes (specificity = 0.6829)
- Oversampled training set using ROSE package to account for data imbalance and low specificity (model did not improve)

![](/images/stoke_by_age_and_gender.png)

Confusion matrix of RF model

| Prediction  | Yes         | No          | 
| ----------- | :---------: | :---------: | 
| Yes         | 28          |  2          | 
| No          | 13          |  1244       | 



---




### [Database Design and R Shiny Dashboard](https://github.com/GrahamChalfant/Data_Management_Project)

#### Database Design

- Built SQL relational database based on hotel business problem 
- Created ER diagram in order to determine entities, relationships, and cardinalities 
- Used diagram to guide database creation in r-studio using the RSQLite package 

Below is the ER diagram created for this project. 

![](/images/ER_diagram.png)

#### R Shiny Dashboard

- Generated R script to scrape XML API hygiene rating data from UK Food Standard Agency API
- Used dplyr to clean and format > 500,000 observations from Food Standard Agency  
- Visualized geolocation data and hygiene ratings and business types using mapdeck and ggplot2, respectively

![](/images/shiny_dash_final.png)



---



### [Business Statistics Assessment](https://github.com/GrahamChalfant/Business_Statistics)

- Used Null Hypothesis Significant Testing and Estimation approach to measure influence marketing campaign had on grocery stores  
- The new marketing campaign (intrial) influenced grocery store's sales gain t(483.08) = -5.7173, P-value = 1.44e-08  

**95% confidence intervals for percent sales gain** of each store controlling for the outlet type, marketing campaign (intrial), and staff turnover.


![](/images/percent%20sales%20gain%20controlling%20for%20outlettype%20and%20staff%20turnover.png)

 
 
 ---
 
 
 
### [MLR Variable Selection Visulization](https://github.com/GrahamChalfant/Advanced_Data_Analysis_Project)

- Used MLR in order to determine the influence of each predictor variable on the outcome variable
- Found r-squared of each independent variable using loops
- Rearranged data using dplyr to order variables in order of r-squared
- Created MLR adding each independent variable, one at a time, based on r-squared in descending order using a loop
- Visualized MLR's adjusted r-squared by each variable added in order to determine the optimal number of variables 

**Adjusted r-squared per variable added to MLR.** The final model needed to consider two things: total adjusted r-squared and the principal of parsimony. From the below image, I felt that the optimal model contained all variables until "TotalHours." This model had an adjusted r-squared which was 1% less than the maximum but contained three fewer variables. 

![](/images/multiple_lm_rsquared.png)

 
 
 ---
 
 
 
 
### [Customer Transaction Prediction Project](https://github.com/GrahamChalfant/Customer_Transaction_Prediction_Project)

- Found optimal ML models by testing different partition sizes, variables using information gain, and various sampling methods
- Defined best performing model using accuracy, recall, f-score, and precision
- Created cost matrices based on the business problem to estimate profit for each model in a high and low-cost scenario 

The graph below shows each models accuracy, f-score, precision, and recall. 
![](/images/AIP_Model_Comparison.png)

The graph below shows the two cost scenarios which were estimated based on annual mortgage payments in the UK. Profits would be mortgage payments received by the bank, and costs are advertising costs. 
![](/images/AIP_Confusion_Matrix_Costs.png)

