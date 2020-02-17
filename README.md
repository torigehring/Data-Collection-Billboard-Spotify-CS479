# Data-Collection-Billboard-Spotify-CS479
This data collection proposal is driven by the question: “What traits do popular songs share?”. The music industry could benefit financially from doing statistical analysis on Spotify and Billboard Hot 100 data (Spotify, 2020; The Hot 100, 2020). Using simple python scripts to scrape the song titles of the Billboard Hot 100, and using Spotify’s python API, I can obtain data such as the song titles, artists, song duration, and genre of the most popular music (Spotipy, 2020; Billboard Hot 100 Web Scraper, 2020). Using this data, I can begin to investigate questions such as: What is the most popular genre? What is the most popular length? I can also explore possible similarities amongst successful songs. These findings could help influence music creators to produce more profitable music. 

This idea was inspired by the work of Sean Miller who collected data about songs in the hot 100 from 8/2/1958 and 12/28/2019 (Miller, 2020). I will be generating a data set by pulling data from already existing data sources: Billboard’s Hot 100 and Spotify’s internal database. This dataset will be a mix of qualitative and quantitative data about popular music tracks. From there I can investigate the characteristics of successful music.

## Metadata
See metadata folder.
Collected on 16 February 2020 by Victoria Gehring

## The Data on GitHub is a subset of the data due to size constraints
Originally the plan was to include 100 songs from years 2015-2019
This repository only contains roughly 30 songs from 2019
The rest are kept locally

## File naming convention:
audio_features[year-of-song]_[song-title].json

## Directory Structure
metadata data scripts
  data: top_songs_year
    top_songs_year: audio_featuresyear-of-song_song-title.json (100 per year)
  metadata: all metadata associated with data collection
  scripts: all code involved with data collection

## References
Billboard Hot 100 Web Scraper. GitHub, Inc 2020. Retrieved from https://github.com/jsubroto/billboard-hot-100-web-scraper
Get a Track. January, 2020. Spotify for Developers. Retrieved from https://developer.spotify.com/documentation/web-api/reference/tracks/get-track/
Dublin Core Metadata Initiative. DCMI. 14 June 2012. Retrieved from https://www.dublincore.org/specifications/dublin-core/dces/
Metadata Types and Functions. n.d. Retrieved from https://marciazeng.slis.kent.edu/metadatabasics/types.htm 
Mets. The Library of Congress. 17 January 2019. Retrieved from http://www.loc.gov/standards/mets/
Miller, Sean. Billboard Hot Weekly Charts. Data.World, Inc 2020. Retrieved from https://data.world/kcmillersean/billboard-hot-100-1958-2017
NumPy. NumPy Developers, 2020. Retrieved from https://numpy.org/
Pandas: Powerful Python Data Analysis Toolkit. Pandas 0.25.3 Documentation. Retrieved from https://pandas.pydata.org/pandas-docs/stable/
Spotify. January, 2020. Spotify AB. Retrieved from https://www.spotify.com/us/ 
Spotify Developer Terms of Service. Version 5, 11 December 2018. Spotify AB, 2020. Retrieved from https://developer.spotify.com/terms/#iii
Spotipy. January 2020. GitHub, Inc. Retrieved from https://github.com/plamere/spotipy
The Hot 100. Billboard. January 2020. Retrieved from https://www.billboard.com/charts/hot-100
Web API. Spotify AB, 2020. Retrieved from https://developer.spotify.com/documentation/web-api/
Website Terms of Use. Billboard, 2020. Retrieved from https://www.billboard.com/p/website-terms-of-use
Harlan, Alex. Scraping Billboard Top 100 on Wikipedia. 9 March 2018.Retrieved from https://alexforrest.github.io/scraping-billboard-top-100-on-wikipedia.html
