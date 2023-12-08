## GEOG5995M-Final-Project
# Background/Context of project
This project provides a framework for local authorities to assess and monitor the variable which has the strongest link to air quality. It can be used and adapted by any local authorities/stakeholders who wish to identify which dimension from the CDRC's AHAH multi-dimensional index may be contributing to poorer health-related features of local areas (LSOA's). 

## What data the GitHub repository contains
Jupyter notebook
AHAH Index CSV file
UK data service LSOA 2011 CSV file
Geoportal gov zip containing shape file

## What the code aims to do
The code walks the user through the data science process through reading in appropriate packages and files, checking and cleaning the data, identifying the variable with the strongest correlation to air quality, visualising the relationship between the identified variable and air quality and finally plotting the variables actual and relative spatial distribution on a map. The initial framework identifies nitrogen dioxide as being the dimension most strongly correlated with air quality across the nation. The analysis then plots the relationship between York's air quality total score and nitrogen dioxide levels, visualising a strong positive correlation, indicating that as the air quality score increases (indicating poorer air quality), the nitrogen dioxide levels also increase. A subplot was then created to visualise the spatial distribution of nitrogen dioxide levels across York's LSOA's with a complementary subplot created to provide the reader with a means to compare York's nitrogen dioxide levels against the UK's. 

To interpret CDRC's AHAH multi-dimensional index, accompanying documentation can be found here: https://www.sciencedirect.com/science/article/pii/S1353829218303563
