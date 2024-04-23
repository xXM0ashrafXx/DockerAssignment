# DockerAssignment
data analysis using jupyter notebook on Docker container on Books dataset 

Harry Potter Books Analysis

This Python script aims to analyze the Harry Potter book series using data from a provided CSV file (books.csv). It utilizes the Pandas library for data manipulation and analysis.

Understanding the Code

1-Loading the Dataset: The script reads the provided CSV file (books.csv) into a Pandas DataFrame.

2-Data Cleaning and Preprocessing: It cleans the data by converting the 'ratings_count' column to numeric and the 'average_rating' column to float. Rows with 
missing values in the 'title', 'ratings_count', or 'average_rating' columns are dropped.

3-Filtering Harry Potter Books: It filters the DataFrame to focus only on books from the Harry Potter series using string matching on the 'title' column.

4-Finding the Most Selling Books: It identifies the top 10 selling books within the Harry Potter series based on the 'ratings_count' column.

5-Calculating Average Rating: It calculates the average rating of all Harry Potter books.

6-Displaying the Results: The script prints out the titles and ratings counts of the most selling Harry Potter books, as well as the average rating of all Harry Potter books.
