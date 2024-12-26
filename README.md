# Music Tags Dataset 🎶

This repository contains a comprehensive collection of song data, including tags and metadata, for tracks spanning from the 2000s to the present day. The tags were extracted using the **Last.fm API** and **Genius Web Scraping**, making this dataset a valuable resource for music analysis, recommendation systems, or any project related to music and its metadata.

## Datasets Overview
### 1. **Genius Metadata**  
These files contain metadata related to **Genius-specific tags**. Genius tags are often based on lyrics and themes, such as mood, genre, and other descriptive tags.

- `genius_metadata.zip`  
  Contains the first part of the Genius tags dataset for various songs.
- `genius_metadata_2.zip`  
  Contains the second part of the Genius tags dataset, complementing `genius_metadata.zip`.

### 2. **Last.fm Metadata**  
These files contain **Last.fm-specific tags**. Last.fm tags are user-generated and are based on listening behavior, genre, and other user-generated content.

- `lastfm_metadata.zip`  
  Contains the first part of the Last.fm tags dataset for various songs.
- `lastfm_metadata_2.zip`  
  Contains the second part of the Last.fm tags dataset, complementing `lastfm_metadata.zip`.
- `lastfm_metadata_3.zip`  
  Contains the third part of the Last.fm tags dataset, further extending the metadata from the previous two files.

### 3. **Merged Last.fm and Genius Metadata**  
These files contain songs for which both **Last.fm** and **Genius** tags have been extracted. This group includes entries that have data from both sources, making it easier to analyze songs with both sets of tags.

- `lastfm_genius_metadata.zip`  
  Contains the first part of the dataset where both Last.fm and Genius tags are available for the same songs.
- `lastfm_genius_metadata_2.zip`  
  Contains the second part of the dataset, complementing `lastfm_genius_metadata.zip` with additional songs that have both Last.fm and Genius tags.

---

## Song Datasets Used
This repository utilizes the following song datasets, which are sourced from Kaggle. These datasets provide metadata about songs, including attributes like artist, song title, genre, and other audio features. Below are the details of each dataset:

### 1. **[Spotify 12M Songs](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs)**  
This dataset contains data for 12 million songs on Spotify. It includes various attributes related to the tracks, such as:
- **Artist**: The artist of the song.
- **Song Title**: The name of the track.
- **Genre**: The genre(s) associated with the track.
- **Audio Features**: Includes attributes like danceability, energy, key, loudness, and more.

This large-scale dataset is ideal for analyzing song features, building recommendation systems, and conducting audio analysis.

### 2. **[Spotify 1 Million Tracks](https://www.kaggle.com/datasets/amitanshjoshi/spotify-1million-tracks)**  
This dataset contains 1 million tracks from Spotify. Key attributes include:
- **Artist**: The name of the artist.
- **Song Title**: The title of the song.
- **Audio Features**: This includes attributes like acousticness, instrumentalness, tempo, and more.
- **Popularity**: A score indicating the popularity of the song based on Spotify’s data.

This dataset is more compact than the 12M dataset but still provides a wealth of information for music data analysis and feature engineering.

---

## Sources:
- **Last.fm API**: Used to fetch song and artist data, including tags based on user-generated content and listening behavior.
- **Genius Web Scraping**: Scraped Genius.com for additional metadata and tags, including lyrics-based tags, mood descriptors, and genre-related information.

---

## Features
- **Comprehensive coverage**: The dataset spans multiple decades, from the 2000s to the present day, ensuring diversity in genres and artists.
- **Multi-source tags**: Each song entry contains tags extracted from both Last.fm and Genius, offering a broad range of insights into each track's characteristics.
- **Easy to use**: The dataset is structured in a way that makes it easy to load and integrate into data analysis, machine learning models, or other applications.

## How to Use
1. **Download the Dataset**:
   - You can download the dataset directly from the repository. The data is available in formats such as `.csv`, `.json`, or `.txt` for easy integration into your project.

2. **Load the Data**:
   - The dataset can be loaded into any data processing tool or software such as Python (using `pandas`), R, or even Excel. Example code to load the data in Python:

   ```python
   import pandas as pd

   # Load dataset
   dataset = pd.read_csv('path/to/dataset.csv')

   # Check the first few rows
   print(dataset.head())

---

## License
This dataset is free to use for educational, research, and non-commercial purposes. Please give credit to the sources when using or sharing the data.

- **Last.fm**: [Last.fm API](https://www.last.fm/api)
- **Genius**: [Genius](https://genius.com/developers)

---

## Contribution
If you want to contribute to this repository, feel free to fork the project and submit a pull request with any updates or improvements. All contributions are welcome!

---

## Disclaimer
This dataset was generated using publicly available APIs and web scraping techniques. While the data was collected in good faith, we do not guarantee its completeness or accuracy. Please use it responsibly.
