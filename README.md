# Recommendations_IBM
In this project, a recommendation system has been designed to recommend papers to the student for IBM students. This project includes two “.csv” data set that one can find in data folder. Because this project is third project in the Udacity data scientist nanodegree, some lines of the code is for testing the code. The “project_tests”, “user_item_matrix”, “top_5”, “top_10” and “top_20” files are needed for those sections of the code. This recommendation projects includes four components. 

##1.	Exploratory Data Analysis
This section provides some insight into the descriptive statistics of the data. Checking the geometry of the data frame and finding data statistics to become familiar with the data. Checking for duplicates and null values. Creating a visualization to see how the number of articles that interact with users is distributed. 

##2. Rank Based Recommendations
This section of the code generates recommendations depending on the article's rank. We don't have any ratings for whether or not a user enjoyed an article in this data set. Only the fact that a user has engaged with an article is known. In these instances, an article's popularity can only be determined by how many times it was engaged with.

##3. User-User Based Collaborative Filtering 
In this part of the code, several function has been created to recognize the similar users and recommend articles based on their similarity. 

##4. Matrix Factorization
In this part of the notebook, a matrix factorization makes article recommendations to the users on the IBM Watson Studio platform.
