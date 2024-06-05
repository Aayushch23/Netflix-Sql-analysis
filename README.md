Netflix SQL Project by Aayush Choudhary
Introduction
This SQL project explores the Netflix dataset to extract valuable insights and perform various data analysis tasks using SQL queries. The dataset includes information about Netflix titles such as show ID, title, type, release year, duration, country, rating, and more.
Setup
Create a database named db.
Import the Netflix dataset into the netflix table.
Queries
Basic Queries
List all titles with their show_id, title, and type.
Display all columns for titles that are Movies.
List TV shows released in the year 2021.
Find all titles where the description contains the word "family".
Count the total number of titles in the dataset.
Advanced Queries
Find the average duration of all movies (in minutes).
List the top 5 latest titles based on the date_added.
List all titles along with the number of other titles by the same director.
Find the total number of titles for each country.
Categorize titles into Family, Kids, and Adult based on their rating.
Additional Queries
Add a new column title_length to calculate the length of each title.
Find the title with the longest duration in minutes.
Create a view named RecentTitles including titles added in the last 30 days.
Rank titles based on their release year within each country.
Calculate the cumulative count of titles added each month.
Write a stored procedure to update the rating of a title given its show_id and new rating.
Find the country with the highest average rating for titles.
Find pairs of titles from the same country where one title has a higher rating than the other.


