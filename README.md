# Readme
# Table of Contents
1.	Installations and package requirement
2.	Project Motivation
3.	File Descriptions
4.	Licensing, Authors and Acknowledgments

# Installations and package requirement
The code is in Python 3.7.6 in Jupyter notebook. The Python libraries applied are numpy, pandas, matplotlib, seaborn and collections. The Anaconda distribution of Python covers the above requirements. 

# Project Motivation
The questions that have been explored/answered relate to if computer science has steadily gained popularity in the last 10 years or if there are there any noticeable trends in the field of computer science. The specific questions I was interested to answer were: 

Q1. Has the participant country representation increased over the decade?
Q2. Is there any noticeable trend in participant Major or Undergraduate representation from non-computer science disciplines especially fine arts, health science or natural science?
Q3. Have the top five popular programming languages changed from year to year since 2011?

To answer these questions, I have used Stack Overflow Annual Developer Survey data from 2011 to 2020 for the time period. The data has been accessed from the following link: https://insights.stackoverflow.com/survey The participation and survey questions have continued to be developed or changed since 2011 and therefore vary from survey to survey which has been considered during the analysis.The survey datasets were individually explored, data for relevant questions was extracted, cleansed and combined to answer the questions. The Project1.ipynb notebook includes the detailed analysis and relevant visualisations.

# File Descriptions
There are ten .csv datafiles for Stack Overflow Annual Developer Survey data from 2011 to 2020 which are included in the Stack Overflow Survey Results zip-folder. 2011 and 2012 .csv files were opened and converted in Notepad++ to utf-8 codec first. The files in the zip-folder are ready to be used with Project1.ipynb file. 

The raw files if required are at: https://insights.stackoverflow.com/surve

The following are directory and survey data file names for data files contained in the Stack Overflow Survey Results zip-folder:

2011 Stack Overflow Survey Results -> 2011 Stack Overflow Survey Results.csv
2011 csv file has been first converted to utf-8 codec in Notepad++.

2012 Stack Overflow Survey Results -> 2012 Stack Overflow Survey Results.csv 
2012 csv file has been first converted to utf-8 codec in Notepad++.

2013 Stack Overflow Survey Responses -> 2013 Stack Overflow Survey Responses.csv

2014 Stack Overflow Survey Responses -> 2014 Stack Overflow Survey Responses.csv

2015 Stack Overflow Developer Survey Responses -> 2015 Stack Overflow Developer Survey Responses.csv

2016 Stack Overflow Survey Results -> 2016 Stack Overflow Survey Responses.csv 

developer_survey_2017 -> survey_results_public.csv

developer_survey_2018 -> survey_results_public.csv

developer_survey_2019 -> survey_results_public.csv

developer_survey_2020 -> survey_results_public.csv

The Project1.ipynb notebook contains the necessary scripts to read, cleanse, filter/join and analyze the data for this project.

# Results
The main findings of the project can be found [here](https://prabhmit-chadha.medium.com/trends-in-computer-science-4c6ec3e78695).

# Licensing, Authors and Acknowledgments
Stack Overflow Annual Developer Survey, Stack Overflow, accessed 5 May 2020,
https://insights.stackoverflow.com/survey

jjrunner/stackoverflow/HowToBreakIntoTheField.ipynb, accessed 9 May 2020, https://github.com/jjrunner/stackoverflow/blob/master/HowToBreakIntoTheField.ipynb

Introduction to Data Science, Data Scientist Nanodegree Program, Udacity, https://www.udacity.com/course/data-scientist-nanodegree--nd025 
