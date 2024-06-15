Accenture North America - Data Analytics and Visualization Job Simulation

# SOCIALBUZZ 
CASE STUDY: The objective to start our engagement with Social Buzz, running a 3 month initial project in order to prove to them that we are the best firm to work with. They are expecting the following: 
- An audit of their big data practice 
- Recommendations for a successful IPO 
- An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity 

### TASK 1 - PROJECT UNDERSTANDING
- Understand the client and business problem at hand.
- Identify the requirements that need to be delivered for this project.
- Identify which tasks you should focus on as a Data Analyst.

##### The business problem tasked to address for this project is - The client has reached a massive scale within recent years and does not have the resources internally to handle it.
The client stated that scale was a big problem of theirs and they are struggling to manage the scale with the resources that they currently have. The brief said that the client is looking for help with the management of their journey into such a large scale. 

##### The three requirements tasked to fulfill for this project is Audit of big data practice, recommendations for IPO, analysis of popular content
##### The most relevant to work on as a data analyst - Analysis of sample data sets with visualizations to understand the popularity of different content categories

### TASK 2 - DATA CLEANING & MODELING
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
1. Content - 
2. Reactions -
3. Reations Type - 
##### STEP2: Clean the data by:
1. removing rows that have values which are missing,
2. changing the data type of some values within a column, and
3. removing columns which are not relevant to this task.
      Think about how each column might be relevant to the business question you’re investigating. If you can’t think of why a column may be useful, it may not be worth including it.
##### STEP3 - Your end result should be three cleaned data sets. 
Cleaned Datasets - 
1. Content
2. Rections -
3. Reactions Type

#### Data Modelling
##### STEP1 - Create a final data set by merging your three tables together
Use the Reaction table as your base table, then first join the relevant columns from your Content data set, and then the Reaction Types data set.
Hint: You can use a “VLookUp” formula
 ##### STEP2 - Figure out the Top 5 performing categories
Add up the total scores for each category.
Hint: You can use the “Sum If” formula
The end result should be one spreadsheet which contains:
- cleaned dataset -

### TASK 3: DATA VISUALIZATION AND STORY TELLING
Prepare a Powerpoint Presentation, 
For each slide, think about: 
- Agenda - What will your presentation cover?
- Project Recap - What are the key points from the brief?
- Problem - What is the problem that you answer in this presentation?
- The Analytics team - Who is on your team? As a reminder from the earlier task - this includes: Andrew Fleming (Chief Technical Architect), Marcus Rompton (Senior Principle), and yourself!
- Process - How did you complete your analysis?

We know that the client wants to understand the top 5 content categories. There are also some other interesting insights that we might want to share with them. For example:
- How many unique categories are there?
- How many reactions are there to the most popular category?
- What was the month with the most posts?
###### Powerpoint Presentation - https://github.com/Jyosna059/Accenture-Data-Analytics-Virtual-internship-Project/blob/8344a2ab11696f6226fd2b7138abb2b589f93479/Power%20Presentation%20-%20Social%20Buzz.pptx
###### Data Analysis and Visualization - https://github.com/Jyosna059/Accenture-Data-Analytics-Virtual-internship-Project/blob/5c52482c97d2fee25936c8f12914d61ef212d23a/Data%20Analysis%20-%20Social%20Buzz.xlsx
1. Analysis - Animals and Science are the two most popular categories of content, showing that people enjoy “real-life” and “factual” content the most.
2. Insights - Food is a common theme with the top 5 categories with “Healthy Eating” ranking the highest. This may given an indication to the audience within your user base. You could use this insight to create a campaign and work with healthy eating brands to boost user engagement.

### TASK 4: PRESENT TO THE CLIENT
When presenting to the client there are a few things that you should remember:
- They may not all be familiar with data, so you need to make sure you talk to them in business-friendly language. 
- You want to show them that you’ve understood their business and requirements, so use their terminology and language relevant to the task. 
- This is your time to shine and to show them how great you are! Try to present your work with confidence and conviction, if you don’t feel confident talking about your results then it’s a good indication that you don’t understand them fully or may need to revisit the dataset! Speaking about your results should feel natural when you explain what you’ve done.
- A good presentation always takes a lot of preparation. The more you practice presenting your content, the more confident you will be when the time comes. Practice with your housemates, friends, family, anyone that is free! Ask for feedback and keep improving until you’re happy with your presentation and you’re confident in presenting your content.
