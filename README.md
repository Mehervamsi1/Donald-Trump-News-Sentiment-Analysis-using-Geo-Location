Project Overview: News Analysis and Visualization
Project Goal
The goal of this project is to fetch news articles using the NewsAPI, perform sentiment analysis on the articles, geolocate them based on their sources, and visualize the sentiment results on an interactive map.

Project Components
Fetching News Articles:

Utilize the NewsAPI to gather news articles related to a specific topic, in this case, "Trump".
Handle pagination and API rate limits to fetch a substantial number of articles.
Sentiment Analysis:

Employ VADER (Valence Aware Dictionary and sEntiment Reasoner) for sentiment analysis.
Categorize each article as positive, neutral, or negative based on sentiment scores.
Geolocation:

Use the OpenCage Geocoder API to extract latitude and longitude coordinates from the sources of the news articles.
Map these coordinates to visualize where the news is originating from.
Interactive Map Visualization:

Utilize Folium, a Python library for creating interactive maps, to plot markers for each news article on a map.
Color-code markers based on sentiment analysis results (green for positive, grey for neutral, red for negative).
Technologies Used
Python Libraries:

requests for making API requests.
pandas for data manipulation and analysis.
vaderSentiment for sentiment analysis.
folium for creating interactive maps.
APIs:

NewsAPI for fetching news articles.
OpenCage Geocoder for geolocating news sources.
Project Workflow
Data Collection:

Fetch news articles using the NewsAPI, iterating through multiple API keys to overcome rate limits and fetch a larger dataset.
Data Processing:

Perform sentiment analysis on the fetched articles using VADER.
Geolocate the articles' sources using the OpenCage Geocoder API.
Visualization:

Display the geolocated news articles on an interactive map using Folium.
Color-code markers on the map based on sentiment analysis results to visually depict the sentiment distribution.
Project Outcome
The project will culminate in an interactive visualization where users can explore news articles related to "Trump", view their sentiment analysis results, and see their geographical distribution.
