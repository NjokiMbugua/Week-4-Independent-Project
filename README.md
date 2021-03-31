# Week-4-Independent-Project
Colab notebook-python data analysis
## Business Overview
Autolib' is an electric car sharing service which was inaugurated in Paris, France, in December 2011. It’s operated by the Bolloré industrial group, and complements the city's bike sharing system, Velib', which was set up in 2007. The Autolib' service maintains a fleet of all-electric Bolloré Blue Cars for public use on a paid subscription basis, employing a citywide network of parking and charging stations.(link). 
## Business Objective
As a data scientist working for the electric car sharing service company, I have been tasked to process station data to understand electric car usage over time.
The main objective of this job assignment is to identify the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018.
## Business Success Criteria
A critical analysis of the data provided to determine the peak hours for blue car pick up and the most popular pick up stations in order to be able to draw a solid plan on how to improve the blue car carrier services.
## Data Understanding Overview
For this project, we are using the availed dataset  by the company. The data set contains useful information on the hours of operation, postal code, dates,time,number of cars operating, charging slots, name of the stations and their rental status.
# Data Preparation 
These are the steps followed in preparing the data 
## Loading Data 
Loaded the autolib dataset from the CSV and then created a Python database. 

## Cleaning Data
The data was checked for validity and some irrelevant data was realized.They were cross checked to ensure that they held no significance to the analysis outcome and thus they were  dropped from the dataframe. The date and time column were merged to one  column named ‘datetime’. For consistency and completeness, the data was checked for null and duplicated values and they were nonexistent. Additionally, a uniformity check was performed and several columns were renamed. 
## Exporting the data to csv file
This step involved converting the already cleady data frame to a csv file and uploading it.
## Analysis
The data was analysed using python to answer key research questions as follows: 
i)What station is the most popular at the most popular picking hour?
ii)What station is the most popular overall?
iii)What postal code is the most popular for picking up Blue cars overall?Does the most popular station belong to that postal code?
iv) What postal code is the most popular for picking up Blue cars at the most popular picking hour?
 
## Key research findings
From the results yielded from the data analysis Ãpinay-sur-Seine/Foch/53 was found to be the most popular station at the most popular picking hour. Paris/Porte de Montrouge/8 was the overall most popular station.The overall popular post code for picking up blue cars was 93100. And postal code 75015 was found to be the most popular postal code for picking up blue cars at the most popular picking hour. Hour 11 was the most popular hour for picking up the blue cars.
 
# Recommendations
From the research findings we deduce that the popular stations were Ãpinay-sur-Seine/Foch/53 and  Paris/Porte de Montrouge/8 and the most popular hour for the blue cars was hour 11. Thus paying keen interest in these two stations would help improve services rendered to the clients such as increasing the number of charging slots, increasing the number of slots(parking space) within these stations in order to have a higher holding capacity.
 
# Evaluation
The job assignment was successful and satisfactory. The datasets provided were up-to-date and contained just the right information which was very useful for the analysis. We were able to address the research problems and subsequently the objectives. And thus make recommendations from supportive evidence.
