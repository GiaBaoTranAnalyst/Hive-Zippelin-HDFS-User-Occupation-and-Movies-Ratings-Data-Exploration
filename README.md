# Hive-Zippelin-HDFS-User-Occupation-and-Movies-Ratings-Data-Exploration
## Introduction:
In this project, the objective was to analyze the correlations between "User, Occupation, Movies, and Ratings" dataset using Apache Hive. Hive's SQL-like query language and MapReduce framework were used to process and analyze the data, making it simpler to work with massive datasets. The analysis' main goals were to present a thorough breakdown of the data and unearth significant trends and user preference insights.

The First Step in the analysis was to load data into Hive through the HDFS system. After then, the data was presented in a tabular format so that it could be visually inspected. The table's schema, which offers a systematic overview of the variables and data types in the dataset, was printed as the next step.

To analyze the correlation and meaning behind the dataset I will go through four ideas. Firstly, only observations with a user's age of more than 25 and a given occupation were displayed after the data had been filtered. This made it easier to pinpoint the most pertinent information and spot patterns in consumer preferences.

The number of users in each occupation was then computed once the data had been grouped by occupation. This allowed the analysis to identify the occupations where the most users were engaged and where the preferences were the strongest by providing a summary of the data by occupation.

The user with the most ratings, along with their age and user ID, were found using the data. This gave important information about the users who rated films the most frequently, which was useful for figuring out their preferences.

## Tools Used:
- Ambari
- Apache Hive

## Project Screenshots
- Question 1: Find out the Occupation of all the users

![image](https://user-images.githubusercontent.com/132706047/249646676-b935853b-cfe1-431b-a411-194c325dedb4.png)




- Question 2: Find out numbers of non-adults (users with ages less than 18) who have rated movies

![image](https://user-images.githubusercontent.com/132706047/249646336-56cffeda-0eb4-4c7a-b970-ced6f4d3aa8f.png)

- Question 3: Find out the count of users by occupation where the user age is more than 25

![image](https://user-images.githubusercontent.com/132706047/249646638-b267b61f-0944-472e-a96a-aada17ea283d.png)



Question 4: Find the user id & age of the user with the most number of ratings 

![image](https://user-images.githubusercontent.com/132706047/249646655-1d9e6ffe-e739-49bf-8882-ac15ba621e49.png)
