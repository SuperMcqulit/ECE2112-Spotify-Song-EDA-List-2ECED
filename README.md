# Compilation of Documents (Assessment)

## Overview of the Assessment:

Source of the code: spotify-2023 (Downloadable in Main Branch)

Description: This EDA on the "Most Streamed Spotify Songs 2023" dataset will examine trends in song popularity by analyzing top tracks, artists, genres, and release years. We’ll explore distributions of streams, identify leading genres and artists, and investigate correlations between track features (like duration and release year) and streaming counts. The aim is to highlight which factors drive popularity and uncover key insights into streaming trends for 2023.


## Guide Questions to follow:

You are expected to answer the following questions using your analysis:

Overview of Dataset - 
How many rows and columns does the dataset contain?
What are the data types of each column? Are there any missing values?

Basic Descriptive Statistics - 
What are the mean, median, and standard deviation of the streams column?
What is the distribution of released_year and artist_count? Are there any noticeable trends or outliers?

Top Performers - 
Which track has the highest number of streams? Display the top 5 most streamed tracks.
Who are the top 5 most frequent artists based on the number of tracks in the dataset?

Temporal Trends - 
Analyze the trends in the number of tracks released over time. Plot the number of tracks released per year.
Does the number of tracks released per month follow any noticeable patterns? Which month sees the most releases?

Genre and Music Characteristics - 
Examine the correlation between streams and musical attributes like bpm, danceability_%, and energy_%. Which attributes seem to influence streams the most?
Is there a correlation between danceability_% and energy_%? How about valence_% and acousticness_%?

Platform Popularity - 
How do the numbers of tracks in spotify_playlists, spotify_charts, and apple_playlists compare? Which platform seems to favor the most popular tracks?

Advanced Analysis - 
Based on the streams data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?
Do certain genres or artists consistently appear in more playlists or charts? Perform an analysis to compare the most frequently appearing artists in playlists or charts.


## Assessment Analysis, Explanation, and Process

Analysis: 
This project involves analyzing a dataset of Spotify tracks in 2023. The analysis focuses on different aspects of the dataset, such as the most streamed tracks, platform presence, stream trends, and the relationship between attributes like key, mode, and genre. The project uses Python, specifically Pandas for data manipulation and Matplotlib/Seaborn for data visualization.

Explanation:
The first step in the process was to load the dataset using Pandas. After loading, we ensured that the dataset was clean and ready for analysis by checking for missing or inconsistent data. Exploratory Data Analysis was then performed to understand the dataset better. Various visualizations were created using Matplotlib and Seaborn to support the analysis. For instance, Bar charts for comparing the number of tracks across platforms or like Histograms and box plots for analyzing the distribution of streams.

Process:
1. Data Preparation - Load the dataset such as pd.read_csv('spotify-2023.csv') and cleaning the dataset
2. Data Aggregation - Used different operations to aggregate data and calculate metrics
3. Visualization - Various visualizations helped identify problems such as trends and outliers
4. Analysis - Examined unique correlations between datas
   
## Expected Outputs

Track Count by Platform:
Spotify Playlists had the highest number of tracks, followed by Spotify Charts then Apple Playlists.

![image](https://github.com/user-attachments/assets/cf541b8f-f8a5-4699-9c6c-55eb93152886)


Platform Preferences:
Spotify Charts favored tracks with higher streams, indicating that the found platform have more popular tracks.

![image](https://github.com/user-attachments/assets/f8f4724e-672a-4487-a89d-8923e74261ab)


Key and Mode Influence:
Tracks in Major keys were found to generally have higher streams compared to tracks in Minor keys. 

![image](https://github.com/user-attachments/assets/5a231624-18e4-4cb3-bdae-427c91734239)


Artist Trends:
Certain artists consistently appeared more frequently across platforms, particularly in Spotify Charts and Spotify Playlists.

![image](https://github.com/user-attachments/assets/fa49d271-5d85-4ddf-af77-f2fb23fb73d9)



## Version and Edit History 

- Version 1 - First implementation of cades to the said csv file / Configuration of proper formating

- Version 2 - Added functionality to calculate and display / performed basic data checks

- Version 3.1 - Enhanced the analysis by identifying more problems in the dataset / Provided the complete code for the analysis, along with visualizations and interpretation steps

- Version 3.2 - Use of functions pd.to_numeric() and notnull() methods to clean the dataset / use of function groupby() for computing statistics

- Version 4 - Final Output / All guide questions are answered / No added features
  

# Author's Profile
Name: Charles Ellis S. Reyes

Section: 2ECE-D

Assessment by: Prof. Engr. Ma. Madecheen S. Pangaliman, M.Sc.

Date of Completion: November 9, 2024
