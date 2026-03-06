# LyricaLytics: A Data Analytics Project Using Spotify's Database

This project analyzes music streaming data to uncover patterns in **listener behavior, song characteristics, and genre popularity**. Using Spotify chart data from **2014–2022**, the goal is to understand how factors such as **song duration, explicit lyrics, and regional genre preferences** influence streaming performance.

The analysis combines **data cleaning, database design, exploratory analysis, and visualization** to generate insights that can support **artists, producers, and streaming platforms in making data-driven decisions**.

---

# Project Overview

This project analyzes Spotify streaming data from **2014–2022** to understand what drives music popularity. The analysis focuses on three key factors: **song duration, explicit lyrics, and regional genre preferences**.

Using data cleaning, exploratory analysis, and visualization techniques, the project identifies patterns in listener engagement and provides recommendations for music industry stakeholders.

### Key Questions

* Does **song duration** affect streaming performance?
* Do **explicit lyrics** influence listener engagement?
* Do **genre preferences vary by region**?

---

# Table of Contents

* [Getting Started](#getting-started)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Methodology](#methodology)
* [Results and Insights](#results-and-insights)
* [Key Visualizations](#key-visualizations)
* [Business Recommendations](#business-recommendations)
* [Contributing](#contributing)
* [License](#license)
* [Contact Information](#contact-information)

---

# Getting Started

To run the project locally:

### Clone the repository

```bash
git clone https://github.com/rachelv2/sql-database.git
```

### Navigate into the project folder

```bash
cd Mini-Project-Spotify
```

### Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Launch the notebook

```bash
jupyter notebook
```

---

# Usage

This project explores how musical attributes influence streaming popularity using exploratory data analysis and visualizations.

The analysis includes:

* Song duration analysis
* Explicit vs non-explicit streaming comparisons
* Trends in explicit song releases
* Regional genre popularity patterns

These insights help explain **listener engagement patterns and music consumption trends**.

---

# Project Structure

```
sql-databse│
├── raw_data/
│   ├── charts_info.csv
│   └── data.csv
│
├── csv_tables/
│   ├── chart_country.csv
│   ├── charts_.csv
│   ├── country.csv
│   ├── genre.csv
│   ├── track.csv
│   └── track_genre.csv
│
├── graphs/
│   ├── duration_binned_histogram_tracks_0_6min.png
│   ├── graph_avg-stream_explicit.png
│   ├── graph_avg-stream_song-duration.png
│   ├── graph_region-genre.png
│   ├── graph_trend-explicit.png
│   ├── heatmap_genres.png
│   ├── lineplot_genres.png
│   └── sorted_genre_barchart_horizontal.png
│
├── THE_SPOTIFY.ipynb
├── charts.ipynb
├── spotify_bridge_tables_anne.ipynb
├── spotify-main.ipynb
├── spotify-fixed.ipynb
├── spotify_bridge_tables_anne.ipynb
│
├── Spotify_Diagram_2026-03-05T13_30_25.809Z.sql
├── Spotify_Diagram_2026-03-06T08_58_44.465Z.png
│
└── README.md
```

---

# Methodology

### 1. Data Acquisition

The dataset was sourced from **Spotify chart data (2014–2022)** containing information about tracks, artists, genres, and streaming performance. 

### 2. Data Cleaning & Preparation

Key preprocessing steps included:

* Handling missing values
* Standardizing genre labels
* Mapping country codes to country names
* Organizing the dataset into structured tables

### 3. Database Design

The project uses a relational structure connecting:

* Tracks
* Artists
* Genres
* Charts
* Countries

An **Entity Relationship Diagram (ERD)** was used to visualize these relationships. 

### 4. Exploratory Data Analysis

Key variables explored:

* Track duration
* Explicit lyrics
* Genre categories
* Regional listening patterns

---

# Results and Insights

## Engagement Curve: Song Duration

Analysis shows that song duration follows an **engagement curve**.

Listeners typically prefer songs that are:

* Long enough to feel complete
* Short enough to maintain attention

Songs that are too short may feel unfinished, while very long songs may lead to listener drop-off. 

**Key Insight**

Songs around **3–4 minutes** tend to generate the strongest engagement.

---

## Explicit Lyrics and Streaming Performance

The share of explicit songs increased significantly from **about 5% in 2014 to roughly 27% in 2022**. 

Between **2016 and 2021**, explicit songs consistently achieved **higher average streams** than non-explicit songs.

However, by **2022**, non-explicit songs began outperforming explicit songs, suggesting a possible shift in listener behavior.

---

## Regional Genre Preferences

Genre popularity varies across different regions. While genres such as **Pop and Hip-Hop** perform strongly worldwide, other genres appear more concentrated in specific markets.

This suggests that **regional culture and listening habits influence music consumption**.

---

# Key Visualizations

### Explicit Songs Trend

Shows how the percentage of explicit songs increased over time.

```markdown
![Explicit Trend](visuals/explicit_trend.png)
```

---

### Explicit vs Non-Explicit Streaming Performance

Compares average streams between explicit and non-explicit songs.

```markdown
![Explicit vs Non Explicit](visuals/explicit_vs_nonexplicit_streams.png)
```

---

### Regional Genre Popularity

Displays how genre popularity varies by region.

```markdown
![Regional Genre Heatmap](visuals/regional_genre_heatmap.png)
```

---

# Business Recommendations

Based on the analysis:

* Target **3–4 minute song lengths** for commercial releases to maximize listener engagement.
* Consider **shortened or radio edits** for songs longer than 5 minutes.
* Use **short tracks primarily for social media promotion**, rather than primary streaming releases.
* Maintain a **balanced mix of explicit and non-explicit songs** to reach broader audiences.
* Release **both explicit and clean versions** of songs to increase playlist and distribution opportunities.

---

# Contributing

Contributions are welcome.

To contribute:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

Please ensure that changes maintain clear documentation and reproducible analysis.

---

# Contact Information

For questions, feedback, or collaboration:

**Rachel Vianna, Anne Leschallier de Lisle, Francisca Andrade**
Email: [rachel@moxydox.com]
GitHub: [https://github.com/rachelv2)

