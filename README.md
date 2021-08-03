# Analysing-Network-Trends-in-India.
ANALYSING THE NETWORK TRENDS WITH RESPECT TO DATA SPEED, SIGNAL STRENGTH ACROSS INDIA FOR THE MONTHS OF JANUARY 2020 – SEPTEMEBER 2020.  

## Introduction

  The world has advanced rapidly in the past decade, every bit of technology that is introduced in the world has been adapted by people for their convenience. One of the most game changing trends that technology has bought about is connecting people from across region and around the world. Networks and network providers play a significant role in the same. Different networks come with varying features but with the same purpose, to connect and provide steady network irrespective of the region. 
  
  With Network and Network providers come an imminent procedure of people choosing which network they can best use, when in a particular region. Network providers vary in terms of signal strength, download speed, data rate per mbps speed and so forth. 
 
 I have come up with few visualization techniques which gives insights into which Network works best according to signal strength, data speed and etcetera region wise in order to give a structure analysis and understanding of how it works region to region across India and also, we derive the comparisons.
 
 
## Methodology Used

  The test sample consisted of data collected from user’s devices through the application “MySpeed” from the Telecom Regulatory Authority of India (TRAI). The main aim of this application is to get a real-time understanding of consumer’s experience across India through an interactive medium. 

  The data collected was collected for every month from January 2020 to September 2020 and a total of 34,48,203 observations were chosen for analysis after the initial cleaning 
The data cleaning process involved various steps which were performed using packages in Python(Pandas)and RStudio(dplyr and tidyverse).The data was checked for its validity, accuracy, uniformity  and consistency by examining the degree to which the data is close to the true values and by looking for any data-type constraints ,range constraints and mandatory constraints. The initial dataset had recorded several NA under the Data Speed, Signal Strength and the Service Area columns. The NA values in the Signal Strength column corresponds to the device not being able to capture signal and the NA values in Service Area corresponds to the area being unidentifiable. To correct these anomalies the NA values where removed since the data set was huge the removal did not disrupt the accuracy of the result as seen during the univariate analysis. The dataset was also checked for any duplicate values which were removed after checking for any inconsistencies. 

  The data analysis process of the project was done in different stages in order to get a clear understanding of each variable: 
  

![image](https://user-images.githubusercontent.com/71822090/128041998-058cf1b7-6acc-4fd7-b8b2-800725609f38.png)


