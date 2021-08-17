# Graham Chalfant's Projects

## About Me


### Dissertation: Relationship Between Trump's Twitter Sentiment and His Approval Ratings

![](/images/wordcloud_trump_twitter_sentiment.png)

### Social Determinates of Health 


### [Advanced Data Analysis: MLR Analysis](https://github.com/GrahamChalfant/Advanced_Data_Analysis_Project)

**Project At A Glance**
- Used MLR in order to determine the influence of each predictor variable on the outcome variable
- Found r-squared of each independent variable using loops
- Rearranged data using dplyr to order variables in order of r-squared
- Created MLR adding each independent variable, one at a time, based on r-squared in descending order using a loop
- Visualised MLR's adjusted r-squared by each variable added in order to determine the optimal number of variables 

**Adjusted r-squared per variable added to MLR.** The final model needed to consider two things: total adjusted r-squared and the principal of parsimony. From the below image, I felt that the optimal model contained all variables until "TotalHours." This model had an adjusted r-squared which was 1% less than the maximum but contained three fewer variables. 

![](/images/multiple_lm_rsquared.png)



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

### Business Statistics 

 
### [Customer Transaction Prediction Project](https://github.com/GrahamChalfant/Customer_Transaction_Prediction_Project)

- Applied multiple LM models to 

![](/images/AIP_Model_Comparison.png)

There is a typo in the chart below

![](/images/AIP_Confusion_Matrix_Costs.png)

If I could do this project over, I would have narrowed our focus on a smaller number of models.



### Pilot Flying J Data Analysis Competition (Winner) 
- Led team of three to win the competition out of 500 students by assigning work, setting deadlines, framing the business problem, and coaching team on most effective way to present the data
- Created visually impactful Excel workbook using conditional formatting, pivot tables, and INDEX MATCH
- Presented project workbook and insights to the Pilot Merchandising team at the Pilot headquarters


### Denstu Jaguar / Land Rover: Competitor Advertising Spend Deep-Dive 


