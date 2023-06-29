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

![image](https://github.com/GiaBaoTranAnalyst/Hive-Zippelin-HDFS-User-Occupation-and-Movies-Ratings-Data-Exploration/assets/132706047/015e4652-a44b-471c-a7b4-66eb15c1c394)




- Question 2: Find out numbers of non-adults (users with ages less than 18) who have rated movies

![image](https://github.com/GiaBaoTranAnalyst/Hive-Zippelin-HDFS-User-Occupation-and-Movies-Ratings-Data-Exploration/assets/132706047/52c1b30b-7f9d-45d7-a5fd-ebca1df6400a)

- Question 3: Find out the count of users by occupation where the user age is more than 25

![image](https://github.com/GiaBaoTranAnalyst/Hive-Zippelin-HDFS-User-Occupation-and-Movies-Ratings-Data-Exploration/assets/132706047/eabf0e97-9629-48b0-b6a7-b1d3a156044c)



Question 4: Find the user id & age of the user with the most number of ratings 

![image](https://github.com/GiaBaoTranAnalyst/Hive-Zippelin-HDFS-User-Occupation-and-Movies-Ratings-Data-Exploration/assets/132706047/9efd546b-91dd-4b93-a1a6-8422df0f7093)
