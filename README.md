# GNOD Project

# Introduction
This project is centered around the development of a song recommendation system for GNOD, which aims to enhance user experience by suggesting songs similar to the ones they input. The project involves several steps, including web scraping, data collection, unsupervised learning, and the creation of a final recommender system.

# Business Goals

- Understand the mission of GNOD and their existing product Gnoosic.

- Align the project's objectives with the company's strategies and goals.

- Read the case study and the email from the CTO to grasp the project's context.

# Steps Overview
Part 1: Web Scraping Popular Songs

- Scraped the top 100 songs and artists from Popvortex's weekly chart and billboard.

- Stored the information in a Pandas dataframe for further processing.
  
Part 2: User-based Recommender

- Created a recommender where users input a song title.
  
- If the song exists in the list, provided a different random song from the dataset.
  
- Notified the user if the song is not present in the list.
  
Part 3: Collecting Songs & Audio Features

- Aimed to create a diverse collection of songs along with their audio features.

- Collected songs from diverse playlists and albums, from spotify, leveraging exponential growth.
  
Part 4: Unsupervised Learning - Clustering

- Applied clustering techniques on the collected songs (Inertia and Silhouette score).
  
- Clustering allows for more accurate recommendations based on similar audio features.
  
Final Recommender (Part 5)

- The final system takes user input.
  
- Checks if the input song is in the Hot 200 for immediate recommendation.
  
- If not, retrieves audio features using Spotify API and identifies the cluster for recommendations from similar clusters.
