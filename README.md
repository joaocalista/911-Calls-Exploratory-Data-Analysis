
![Logo](https://images.squarespace-cdn.com/content/v1/51dc541ce4b03ebab8c5c88c/1472239169814-XBT5J2JNIYW8B3BSX5F7/image-asset.jpeg?format=1000w)


# Exploratory Data Analysis Using Python


In this project we're going to perform an Exploratory Data Analysis
of 911 Calls from Montgomery County, PA including calls from 2015 to 2020.

Exploratory Data Analysis refers to the critical process of performing 
initial investigations on data so as to discover patterns,to spot anomalies,
to test hypothesis and to check assumptions with the help of summary statistics 
and graphical representations.

### We're going to answer some questions, like:
- How many zipcodes does the dataset have?
- What are the top 5 zip codes for 911 calls?
- What are the top 5 townships (twp) for 911 calls?
- What is the most common reason for a 911 call? 
- What are the top 10 most common coordinate for a 911 call?
- How do calls behave through the week?
- With the help of a map, which region has the most 911 calls?

### The project can be accessed through the link below.

http://nbviewer.org/github/joaocalista/911-Calls-Exploratory-Data-Analysis/blob/main/911_calls_eda.ipynb

## About 911
Created in 2004, the National 911 Program is housed within the National Highway 
Traffic Safety Administration at the U.S. Department of Transportation (DOT).

The 911 system was designed to provide a universal, easy-to-remember number 
for people to reach police, fire or emergency medical assistance from any 
phone in any location. Today, people communicate in ways that the designers 
of the original 911 system could not have envisioned: wireless phones, text 
and video messages, social media, Internet Protocol (IP)-enabled devices and more.

## About Montgomery County
Montgomery County is the third-most populous county in the Commonwealth of 
Pennsylvania, and the 73rd-most populous in the United States. As of the 2020 
census, the population of the county was 856,553.

Montgomery County is located adjacent to and northwest of Philadelphia.
The county seat and largest city is Norristown. Montgomery County is 
geographically diverse, ranging from farms and open land in the extreme north 
of the county to densely populated suburban neighborhoods in the southern 
and central portions of the county.


# About the data

The data was extracted from kaggle.com from the dataset "Emergency - 911 Calls"
by Mike Chirico. The link is provided below:

https://www.kaggle.com/datasets/mchirico/montcoalert

## Feature Columns

- **lat**: String variable, Latitude
- **lng**: String variable, Longitude
- **desc**: String variable, Description of the Emergency Call
- **zip**: String variable, ZIP Code
- **title**: String variable, Title of Emergency
- **timeStamp**: String variable, Date and time of the call, YYYY-MM-DD HH:MM:SS
- **twp**: String variable, Township
- **addr**: String variable, General Address
- **e**: String variable, Dummy variable, Index column (always 1)


## References

 - [Montgomery County, Pennsylvania](https://en.wikipedia.org/wiki/Montgomery_County,_Pennsylvania)
 - [About 911](https://www.911.gov/about/)
 - [What is Exploratory Data Analysis?](https://towardsdatascience.com/exploratory-data-analysis-8fc1cb20fd15)
 - [Tomas Mantero Project](https://www.kaggle.com/code/tomasmantero/emergency-911-calls-exploratory-data-analysis/notebook)