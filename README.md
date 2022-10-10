# SQL_For_Datascience_Yelp_Dataset
Coursera-SQL for Data Science-Yelp Dataset SQL Lookup-Final Project

Part 1: Yelp Dataset Profiling and Understanding

1. Profile the data by finding the total number of records for each of the tables below:
	
i. Attribute table = 10000
ii. Business table = 10000
iii. Category table = 10000 
iv. Checkin table = 10000 
v. elite_years table =10000 
vi. friend table = 10000 
vii. hours table = 10000 
viii. photo table = 10000 
ix. review table = 10000 
x. tip table = 10000 
xi. user table = 10000

Code:
SELECT
(SELECT COUNT(*)FROM Attribute) AS Attribute_count,
(SELECT COUNT(*)FROM Business) AS Business_count,
(SELECT COUNT(*)FROM Category) AS Category_count,
(SELECT COUNT(*)FROM Checkin) AS Checkin_count,
(SELECT COUNT(*)FROM elite_years) AS elite_years_count,
(SELECT COUNT(*)FROM friend) AS friend_count,
(SELECT COUNT(*)FROM hours) AS hours_count,
(SELECT COUNT(*)FROM photo) AS photo_count,
(SELECT COUNT(*)FROM review) AS review_count,
(SELECT COUNT(*)FROM tip) AS tip_count,
(SELECT COUNT(*)FROM user) AS user_count;
