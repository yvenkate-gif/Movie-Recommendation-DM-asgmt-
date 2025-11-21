# Movie-Recommendation-DM-asgmt-

#Project Description

This project implements three different movie recommendation algorithms using the MovieLens 100K dataset to compare various approaches for suggesting relevant movies to users.


#Algorithms Implemented

-- User-Based Collaborative Filtering - Finds similar users and recommends movies they enjoyed

--Item-Based Collaborative Filtering - Recommends movies similar to ones already liked based on rating patterns

--Graph-Based Random Walks (Pixie-inspired) - Explores user-movie network connections through random walks


#File Overview

--Movie_Recommendation.ipynb - Complete Jupyter notebook with data loading, preprocessing, and all three recommendation algorithms

-- users.csv, movies.csv, ratings.csv - Cleaned dataset files exported from the project

--Pixie Explanation.pdf - Detailed explanation of the graph-based random walk algorithm

--Project_Report.pdf - Comprehensive project report with methodology, results, and analysis


#Results Summary

--User-Based Filtering: Perfect accuracy - matched expected results exactly for test cases

--Item-Based Filtering: Strong semantic relevance - found movies with similar themes and genres

--Graph-Based Random Walks: Good for discovery - provided diverse and exploratory recommendations

--All methods produced valid, meaningful movie suggestions that demonstrate different recommendation strategies
