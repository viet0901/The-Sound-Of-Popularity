# 🎵 Spotify Music Analysis  

## 📜 Description  
This project explores the relationship between various musical features and the popularity of songs on Spotify. Using data-driven insights, it identifies key factors that influence a song's success and builds predictive models to uncover patterns in Spotify's 2023 dataset.

---

## 🗂 Table of Contents  
1. [Project Objective](#-project-objective)  
2. [Dataset Overview](#-dataset-overview)  
3. [Methodology](#-methodology)  
4. [Results and Insights](#-results-and-insights)  
5. [Installation and Usage](#-installation-and-usage)  
6. [Contributing](#-contributing)  
7. [License](#-license)  

---

## 🎯 Project Objective  
The primary goal is to analyze Spotify's 2023 music data to determine which musical attributes (e.g., danceability, energy, tempo) correlate most strongly with a song's popularity and to predict potential hit songs using statistical models.

---

## 📊 Dataset Overview  
**Source:** Spotify 2023 Dataset (`spotify-2023.csv`)  
**Features Analyzed:**  
- **Danceability**: Suitability of a track for dancing  
- **Energy**: Song intensity and activity  
- **Loudness**: Volume level  
- **Speechiness**: Spoken word presence  
- **Tempo**: Speed in beats per minute  
- **Streams**: Song play count (popularity metric)

---

## 🛠 Methodology  
### Tools and Libraries:  
- `R` and R libraries: `dplyr`, `ggplot2`, `car`, `lmtest`, `leaps`.  
- Statistical modeling for regression and feature selection.  

### Steps:  
1. **Data Cleaning**: Addressed missing values, removed outliers, and standardized formats.  
2. **Exploratory Data Analysis (EDA)**: Visualized trends and correlations.  
3. **Regression Modeling**: Built models to predict stream counts based on musical features.  
4. **Best Subset Selection**: Identified the most impactful predictors.  

---

## 📈 Results and Insights  
- **Danceability** and **Energy** are strong predictors of a song's success.  
- Tracks with higher speechiness tend to have fewer streams.  
- The optimized regression model explains a significant portion of variability in song popularity.  

Visualizations and additional analysis results are included in the project files.

