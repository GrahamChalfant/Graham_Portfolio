# Graham Chalfant's Projects

## About Me


### [Dissertation: The Power of @realDonalTrump](https://github.com/GrahamChalfant/Dissertation_Power_Of_realDonalTrump)

- Analyzed Trump's 16,000 presidential tweets to measure their influence on his approval ratings
- Created visually informative graphs displaying Trump's Twitter activity and approval ratings over time 
- Calculated Trump's average daily Twitter sentiment using dplyr and a lexicon sentiment analysis approach 
- Used linear regressions to determine the strength of the connection between Trump's Twitter sentiment and approval ratings 


![](/images/wordcloud_trump_twitter_sentiment.png)

### Social Determinates of Health 




### [Data_Management: Database Design and R Shiny Dashboard](https://github.com/GrahamChalfant/Data_Management_Project)

#### Database Design
- Created an ER diagram in order to determine entities, relationships, and cardinalities 
- Used diagram to guide database creation in r-studio using the RSQLite package
- Entered fake data in order to run queries and test the database 

Below is the ER diagram created for this project. 

![](/images/ER_diagram.png)

#### R Shiny Dashboard
- Generated R script to scrape XML API hygiene rating data from UK Food Standard Agency API
- Used dplyr to clean and format > 500,000 observations from Food Standard Agency  
- Visualized geolocation data and hygiene business types and ratings using mapdeck and ggplot2, respectively

![](/images/shiny_dash_final.png)

### [Business Statistics Assessment](https://github.com/GrahamChalfant/Business_Statistics)
- Determined effects new marketing campaign had on supermarket sales data 
- Used null hypothesis testing and the estimation approach to determine the effects of predictor variables on the dependent variable, sales gain 
- The new marketing campaign (intrial) influenced store's sales gain t(483.08) = -5.7173, P-value = 1.44e-08
- The relationship between percent sales gain and the marketing campaign (intrial) and outlet type is statistically significant, but staff turnover is not.   

**95% confidence intervals for percent sales gain** of each store controlling for the outlet type, marketing campaign (intrial), and staff turnover.

![](/images/percent%20sales%20gain%20controlling%20for%20outlettype%20and%20staff%20turnover.png)

 
### [Advanced Data Analysis: MLR Analysis](https://github.com/GrahamChalfant/Advanced_Data_Analysis_Project)
- Used MLR in order to determine the influence of each predictor variable on the outcome variable
- Found r-squared of each independent variable using loops
- Rearranged data using dplyr to order variables in order of r-squared
- Created MLR adding each independent variable, one at a time, based on r-squared in descending order using a loop
- Visualized MLR's adjusted r-squared by each variable added in order to determine the optimal number of variables 

**Adjusted r-squared per variable added to MLR.** The final model needed to consider two things: total adjusted r-squared and the principal of parsimony. From the below image, I felt that the optimal model contained all variables until "TotalHours." This model had an adjusted r-squared which was 1% less than the maximum but contained three fewer variables. 

![](/images/multiple_lm_rsquared.png)

 
 
### [Customer Transaction Prediction Project](https://github.com/GrahamChalfant/Customer_Transaction_Prediction_Project)

- Found optimal ML models by testing different parameter settings for each model, namely partition size, variable selection based on information gain, and various sampling methods
- Defined best performing model using accuracy, recall, f-score, and precision
- Created cost matrices based on business problem to estimate profit for each model in a high and low-cost scenario 


![](/images/AIP_Model_Comparison.png)


![](/images/AIP_Confusion_Matrix_Costs.png)




### Pilot Flying J Data Analysis Competition (Winner) 
- Led team of three to win the competition out of 500 students by assigning work, setting deadlines, framing the business problem, and coaching team on most effective way to present the data
- Created visually impactful Excel workbook using conditional formatting, pivot tables, and INDEX MATCH
- Presented project workbook and insights to the Pilot Merchandising team at the Pilot headquarters

This was my first experience with data analysis. The work itself is outdated, but its a great memory for me!

Below is an advanced filter I created with macros to show sales by month for specific bundles of goods. The idea was that if there was a spike in sales the same month a promotion was applied to said bundle, then the promotion had an impact. The image below is not filtered for a specific bundle of goods. From this we can see that item sales were fairly constant with hints of seasonality. 

![](/images/pilot_flying_j_q4.png)


   







