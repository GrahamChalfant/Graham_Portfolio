# Graham Chalfant Portfolio
## My projects

### [Advanced Data Analysis: Regression Variable Selection ](https://github.com/GrahamChalfant/Advanced_Data_Analysis_Project)

This project challenged my team and I to answer the following questions based on the SkillCraft_Dataset.csv: 

Question 1: What affects the expert level? How can the players improve their level? 
Question 2: Are there any identifiable sets or “groups” of players within the data? If so, what are their distinguishing features? 
Question 3: Investigate the association of the different variables. How many hidden factors are related to these characteristics? Can you interpret these factors?

The SkillSet_Dataset file contains video game telemtric data from a cognitive study of a Complex SKill Leaning project. I was in charge of answering the first question. I accomplished this by the analysis featured below. 

The image displayed below is the r-squared associated with each predictor variable, in descending order. 

![R-sqaured by Variable](https://user-images.githubusercontent.com/70036009/129126071-91d66901-c239-4499-8837-e1a6abe405db.png)

The variables above were then added to a regression model, one at a time, by r-squared. This was done using a loop funcionn - this can be seen by following the link in the project tile. Building a regression model one variable at a time by r-squared was done to determine the variables which should be included in the final model. The visualization below shows how each additianl variable contributed to the adjusted r-squared. 

![Multiple LM R-squared](https://user-images.githubusercontent.com/70036009/129126196-9b064030-e62c-486a-ae9e-93e51074c79e.png)

Not all varaibels were included in the model to adhear to the principal of parciomony. The first 7 varaibles were included in the model based on this principal. Additional variables added after "TotalHours" did not have a significant impact on the adjusted r-squared. 

