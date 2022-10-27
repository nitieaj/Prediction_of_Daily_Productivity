## Project_8-Prediction_of_Daily_Productivity
## Description
### Context

Productivity Prediction of Garment Employees

### Null hypothesis: 


Explore the data for trends in the data  or find any clear indications of relationships between the predictors.

### Content
The medical Garment Industry embeds  new electronic fabrics, blended with conductive materials that are used in high-tech clothes, intelligent medical garments
Applications for the health sector include clothes with external monitoring systems worn by patients with chronic diseases. 
Telemedicine provides the possibility to stay in contact with their health care provider for medical advice.It is a highly labour-intensive industry with lots of manual processes. Satisfying the huge global demand for garment products is mostly dependent on the production and delivery performance of the employees in the garment manufacturing companies. So, it is highly desirable among the decision makers in the garments industry to track, analyse and predict the productivity performance of the working teams in their factories. This dataset can be used for regression purpose by predicting the productivity range (0-1) or for classification purpose by transforming the productivity range (0-1) into different classes

Attribute Information:

1. date : Date in MM-DD-YYYY
2. day : Day of the Week
3. quarter : A portion of the month. A month was divided into four quarters
4. department : Associated department with the instance
5.  team_no : Associated team number with the instance
6. no_of_workers : Number of workers in each team
7. no_of_style_change : Number of changes in the style of a particular product
8. targeted_productivity : Targeted productivity set by the Authority for each team for each day.
9. smv : Standard Minute Value, it is the allocated time for a task
10. wip : Work in progress. Includes the number of unfinished items for products
11. over_time : Represents the amount of overtime by each team in minutes
12. incentive : Represents the amount of financial incentive (in BDT) that enables or motivates a particular course of action.
13. idle_time : The amount of time when the production was interrupted due to several reasons
14. idle_men : The number of workers who were idle due to production interruption
15. actual_productivity : The actual % of productivity that was delivered by the workers. It ranges from 0-1.

Finally, all data was labeled and the class variable NObesity was created with the values of: Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II and Obesity Type III, based on Equation  and information from WHO and Mexican Normativity. 

The data contains numerical data and continous data, so it can be used for analysis based on algorithms of classification, prediction, segmentation and association. 
See paper here: https://www.sciencedirect.com/science/article/pii/S2352340919306985?via%3Dihub
Data is available in CSV format and ARFF format to be used with the Weka tool..

