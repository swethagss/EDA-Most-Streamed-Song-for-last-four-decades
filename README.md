# **Project Overview**

## **1. Introduction**

This project conducts an Exploratory Data Analysis (EDA) on a dataset featuring the most streamed songs from the past four decades. The aim is to reveal insights and trends in streaming behavior, examine the distribution of genres and artists, and carry out hypothesis testing to identify key patterns within the data

![Exploring_Most_Streamed_Songs_EDA](https://github.com/user-attachments/assets/ce6b1742-0cc9-48cd-b568-b131ac2d4595)

## **2. Objectives**

The primary objectives of this porject are:
- To perform data cleaning and preparation.
- To explore the dataset and gain insights into streaming patterns across different decases.
- To analyse the distribution of genres and artists.
- To perform Hypothesis Testing to draw significant conclusions from the data.
- To visualize the data to better understand the underlying patterns and trends.

## **3. Dataset Description**

The dataset used in this project contains various columns representing different attributes of the most streamed songs. Key columns in the dataset include:

- Track: Title of the song.
- Album Name: Name of the album.
- Artist: Name of the artist.
- Release Date: Year the song was released.
- ISRC: International Standard Recording Code.
- All Time Rank: Ranking of the song based on streams.
- Track Score: Score assigned to the track.
- Spotify Streams: Number of times the song has been streamed on Spotify.
- Spotify Playlist Count: Number of playlists the song is featured on Spotify.
- Spotify Playlist Reach: Reach of the playlists the song is featured on Spotify.
- Spotify Popularity: Popularity score on Spotify.
- YouTube Views: Number of views on YouTube.
- YouTube Likes: Number of likes on YouTube.
- TikTok Posts: Number of posts featuring the song on TikTok.
- TikTok Likes: Number of likes on TikTok.
- TikTok Views: Number of views on TikTok.
- YouTube Playlist Reach: Reach of the playlists the song is featured on YouTube.
- Apple Music Playlist Count: Number of playlists the song is featured on Apple Music.
- AirPlay Spins: Number of spins on AirPlay.
- SiriusXM Spins: Number of spins on SiriusXM.
- Deezer Playlist Count: Number of playlists the song is featured on Deezer.
- Deezer Playlist Reach: Reach of the playlists the song is featured on Deezer.
- Amazon Playlist Count: Number of playlists the song is featured on Amazon.
- Pandora Streams: Number of streams on Pandora.
- Pandora Track Stations: Number of stations featuring the track on Pandora.
- Soundcloud Streams: Number of streams on Soundcloud.
- Shazam Counts: Number of times the song has been Shazamed.
- TIDAL Popularity: Popularity score on TIDAL.
- Explicit Track: Indicates if the track is explicit.

## **4. Methodolgy**

The project follows a structure approach to explore and analyze the dataset.

**a. Data Cleaning**

- Handling missing values
- Ensuring consistency in data types
- Removing duplicates
- Creating New Data fields

**b. Data Exploration**
- The data exploration phase involves multiple types of analysis to gain comprehensive insights into the dataset

**i. Univariate Analysis**
- Analysing individual columns to understand their distribution and identify any Outliers.
- Example : Distribuion of Spotify Streams, Youtube Views, Tiktok Views, etc.
 
**ii. Bivariate Analysis**
- Exploring the relationships between two variables
- Example : Correlation between Spotify Streams and Youtube Views etc.

**iii. Univariate Analysis**
- Examining the interactions between multiple variables.
- Example: Analyzing how Spotify Streams, YouTube Views, and TikTok Posts collectively impact the popularity of a song etc

- **c. Visualization**
  - Creating visualizations to represent the data insights.
      - Bar plots, pie charts, line graphs, bubble plots are used to illustrate key findings

  **d. Hypothesis Testing**
  - Performing statistcal tests to draw significant conclusions from the data.
      - Example Hypotheiss : There is significant difference in the average Spotify Streams between songs released in the first half of the year and those released in the second half.

  
## **5. Insights**

Some of the key insights derived from the analysis include:

- Missing Values: Columns like TIDAL Popularity, Soundcloud Streams, and SiriusXM Spins have a high percentage of missing data. Prioritize analysis on the complete columns and consider imputing or addressing the substantial gaps in the others.
- Data Correlation: Strong positive correlations between TikTok metrics (Likes, Views, Posts) and moderate positive correlations between Spotify metrics (Streams, Playlist Count, Playlist Reach).
- Explicit Content: Non-explicit tracks dominate top positions in streams and likes. Artists like Bad Bunny, Doja Cat, Drake, and Kreepa are popular with explicit tracks.
- Artist Popularity: Drake has the highest total playlist count, with Bad Bunny, The Weeknd, and Travis Scott also highly popular.
- Release Patterns: Peak album release period is in March, June and October with significant releases in July and September. Noticeable decline in album releases in April, May and Dec

## **6. Conclusion**

This project showcases the significant influence of streaming platforms on the music industry. Through an analysis of the most streamed songs from the past four decades, it provides valuable insights into the evolution of music consumption. These findings can guide music producers, artists, and industry stakeholders in understanding current trends and anticipating future developments

## **7. Future Work**

Potential areas for future work include:

- Expanding the dataset to include more recent streaming data for a comprehensive analysis
- Analyzing the impact of external factors like social media and marketing campaigns on streaming trends
- Exploring the relationship between streaming numbers and metrics such as concert ticket sales and merchandise revenue



  
