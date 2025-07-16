# 🎵 Spotify Music Analysis

**Author:** Viet Nguyen
**Date:** Spring 2024

---

## 📜 Description

This project explores the relationship between musical features and the popularity of songs on Spotify. Using statistical modeling and data visualization, we identify the most influential traits of a song’s success and build predictive models using Spotify’s 2023 dataset.

---

## 🗂 Project Structure

```
.
├── data/                             # Raw and cleaned datasets
│   ├── songtest.csv
│   ├── songtrain.csv
│   └── spotify-2023.csv
├── markdown/                         # RMarkdown notebook for analysis
│   └── Viet_Nguyen_Final_Project.Rmd
├── presentation/                     # Final presentation slide deck
│   └── 220 Final Presentation - Viet & Nicolas.pptx
├── report/                           # Rendered HTML report
│   └── Viet_Nguyen_Final_Project.html
└── README.md                         # Project documentation
```

---

## 🎯 Project Objective

To analyze Spotify's 2023 music data and determine which musical attributes—such as danceability, energy, and tempo—correlate most with a song's popularity, and to predict future hit potential using regression-based models.

---

## 📊 Dataset Overview

**Source:** Spotify 2023 Dataset (`spotify-2023.csv`)
**Key Features Analyzed:**

* **Danceability:** How suitable a track is for dancing
* **Energy:** Intensity and activity of a track
* **Loudness:** Average volume level
* **Speechiness:** Presence of spoken words
* **Tempo:** Beats per minute
* **Streams:** Number of plays (target variable)

---

## 🛠 Methodology

**Tools & Libraries:**

* `R`, `dplyr`, `ggplot2`, `car`, `lmtest`, `leaps`

**Process:**

* **Data Cleaning:** Handled missing values, outliers, and formatting issues
* **Exploratory Data Analysis:** Correlation plots and visual trends
* **Regression Modeling:** Built multiple linear regression models
* **Best Subset Selection:** Used AIC and adjusted R² to select top predictors

---

## 📈 Results and Insights

* **Danceability** and **Energy** are the strongest predictors of stream counts
* **Speechiness** is negatively associated with popularity
* The final regression model explains a meaningful portion of variance in song streams
* Visual outputs and plots are available in the notebook and presentation files