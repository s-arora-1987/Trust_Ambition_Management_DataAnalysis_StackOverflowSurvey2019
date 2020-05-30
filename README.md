# Analysis for devlopers trust and ambition for management using data from StackOverflow Survey' 2019

For testing this project code, please download the data set files survey_results_public.csv and survey_results_schema.csv from https://insights.stackoverflow.com/survey for year 2019.

Libraries used in project: 

- numpy
- pandas
- matplotlib
- seaborn


Motivation:

The target of this project is to follow CRISP-DM Process (Cross Industry Process for Data Mining) on a public dataset for finding answers to three business questions: 

- As compared to people unsatisfied with their job, do satisfied people show more confidence in their management? 
- As compared to people satisfied with their job, do unsatisfied people show more belief that they need to be a manager to make more money? 
- As compared to people working in large companies, do people working for small size companies show more inclination to becoming managers in future? 


Files:

CRISP_DM_Stackoverflow_Survey_Data.ipynb shows the code for pre-processing data and then using correlation withing fields to answer the questions. 

Summary of analysis:

A high level of job satisfaction is resonably more correlated with confidence in manager, as compared to lowest level of satisfication. The difference between two coefficients of correlation is significant. There is a relation between career satisfaction and managerial ambition for more money, but it is not very strong. It does not seem true that employees in relatively small size orgamizations are more inclined to become managers in future. 

