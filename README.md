## Accenture-Data-Analytics-Virtual-internship-Project
Accenture North America - Data Analytics and Visualization Job Simulation


# SOCIALBUZZ 
CASE STUDY: The objective to start our engagement with Social Buzz, running a 3 month initial project in order to prove to them that we are the best firm to work with. They are expecting the following: 
- An audit of their big data practice 
- Recommendations for a successful IPO 
- An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity 

### TASK1 - PROJECT UNDERSTANDING
- Understand the client and business problem at hand.
- Identify the requirements that need to be delivered for this project.
- Identify which tasks you should focus on as a Data Analyst.

##### The business problem tasked to address for this project is - The client has reached a massive scale within recent years and does not have the resources internally to handle it.
The client stated that scale was a big problem of theirs and they are struggling to manage the scale with the resources that they currently have. The brief said that the client is looking for help with the management of their journey into such a large scale. 

##### The three requirements tasked to fulfill for this project is Audit of big data practice, recommendations for IPO, analysis of popular content
##### The most relevant to work on as a data analyst - Analysis of sample data sets with visualizations to understand the popularity of different content categories

### TASK2 - DATA CLEANING & MODELING
The client has sent through:
7 data sets - each data set contains different columns and values, The data sets are User, Profile, Location, Session, Content, Reaction, Reaction tYpes
A data model - this shows the relationships between all of the data sets, as well as any links that you can use to merge tables.
There is a lot of information. So, to make sure you are using the right data to answer the business questions you’ll follow these steps:
1. Requirements gathering
2. Data cleaning
3. Data modelling

The main step is to use this data model to identify which datasets will be required to answer your business question - which is to to figure out the top 5 categories with the largest popularity.
To identify which content categories are most popular. Popularity is determined based on reaction scores. 
##### Among the 7 data sets, The 3 data sets will you need to complete your analysis - Reaction, Content, Reaction Types
To clarify why you made this selection:
- The brief carefully it states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
- As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
- We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
- So, to figure out popularity, we’ll have to add up which content categories have the largest score.

#### Data Cleaning
##### STEP1 - Open the three data sets below
1.
2.
3. 

##### STEP2: Clean the data by:
1. removing rows that have values which are missing,
2. changing the data type of some values within a column, and
3. removing columns which are not relevant to this task.
      Think about how each column might be relevant to the business question you’re investigating. If you can’t think of why a column may be useful, it may not be worth including it.

##### STEEP3 - Your end result should be three cleaned data sets. 
Cleaned Dataset - 

