# Graham Chalfant Portfolio
## My projects:

### [Advanced Data Analysis: Regression Variable Selection ](https://github.com/GrahamChalfant/Advanced_Data_Analysis_Project)

This project challenged my team and I to answer the following questions based on the SkillCraft_Dataset.csv: 

1: What affects the expert level? How can the players improve their level?
2: Are there any identifiable sets or “groups” of players within the data? If so, what are their distinguishing features? 
3: Investigate the association of the different variables. How many hidden factors are related to these characteristics? Can you interpret these factors?

The SkillSet_Dataset file contains video game telemtric data from a cognitive study of a Complex SKill Leaning project. I was in charge of answering the first question. I accomplished this using a regression model. Key analysis and findings can be seen below.  

The regression model was built by performing a simple linear regression for each variable and then selecting the most informative variables. Variables were selected while considering two things: The variables' r-squared and the total number of selected variables. Building a solid model with informative variables was necessary, but the principle of parsimony also needed to be considered. 

R-squared was chosen over p-value because they were synonymous in this instance, and r-squared
was easier to visualize. 

![R-sqaured by Variable](https://user-images.githubusercontent.com/70036009/129126071-91d66901-c239-4499-8837-e1a6abe405db.png)

The variables above were then added to a regression model, one at a time, by r-squared. This was done using a loop funcionn - this can be seen by following the link in the project tile. Building a regression model one variable at a time by r-squared was done to determine the variables which should be included in the final model. The visualization below shows how each additianl variable contributed to the adjusted r-squared. 

![Multiple LM R-squared](https://user-images.githubusercontent.com/70036009/129126196-9b064030-e62c-486a-ae9e-93e51074c79e.png)

Not all varaibels were included in the model to adhear to the principal of parciomony. The first 7 varaibles were included in the model based on this principal. Additional variables added after "TotalHours" did not have a significant impact on the adjusted r-squared. 

A model in SPSS was built after predictor varaibles were selected in R. SPSS' model results were congruent with the model in R. The only difference was that SPSS deamed "SelectByHotKeys" as insignificnat, so it was removed in the final model. 
