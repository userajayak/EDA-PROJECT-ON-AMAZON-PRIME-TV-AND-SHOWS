[README.md](https://github.com/user-attachments/files/27905581/README.md)
# Amazon Prime TV Shows & Movies - Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Amazon Prime TV Shows and Movies dataset using Python. The main objective is to discover insights, trends, and patterns related to the content available on Amazon Prime Video.

The analysis focuses on:
- Distribution of Movies vs TV Shows
- Most popular genres
- Top producing countries
- Release trends over time
- Content ratings and categories
- Genre-wise content distribution

---

## Dataset

The dataset contains information about Amazon Prime Video titles including:

- Title
- Type (Movie / TV Show)
- Genre
- Release Year
- Country
- Duration
- Rating
- Director
- Cast
- Date Added

Dataset Source: Kaggle - Amazon Prime Movies and TV Shows Dataset

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## Project Workflow

### 1. Data Loading
- Imported dataset using Pandas
- Checked dataset structure and columns

### 2. Data Cleaning
- Handled missing values
- Converted date columns
- Cleaned genre and country columns
- Removed duplicates

### 3. Exploratory Data Analysis
Performed analysis on:
- Content types
- Genres
- Countries
- Release years
- Ratings
- Duration trends

### 4. Data Visualization
Created visualizations using:
- Bar Charts
- Countplots
- Line Charts

---

## Key Insights

### Movies vs TV Shows
- Movies dominate the Amazon Prime catalog.
- TV Shows are significantly fewer compared to Movies.

### Top Genres
- Drama and Comedy are among the most common genres.
- Documentary and Action content are also highly available.

### Top Producing Countries
- United States and India contribute a major portion of the content library.
- International content is growing steadily.

### Release Trends
- Content production increased rapidly after 2000.
- TV Shows experienced noticeable growth in recent years.

---

## Sample Visualizations

### Chart 1 - Top Genres by Type
Comparison of genres across Movies and TV Shows.

### Chart 2 - Distribution of Movies vs TV Shows
Countplot showing content distribution.

### Chart 3 - Top Producing Countries
Bar chart displaying countries producing the most content.

### Chart 4 - Release Trend Over Time
Line chart showing yearly release trends.

---

## Project Structure

```bash
├── EDA_ON_AMAZON_PRIME_TV_SHOWS_AND_MOVIES.ipynb
├── amazon_prime_titles.csv
├── README.md
```

---

## How to Run the Project

### Clone Repository

```bash
git clone https://github.com/userajayak/EDA-PROJECT-ON-AMAZON-PRIME-TV-AND-SHOWS.git
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

### Run Notebook

Open:

```bash
EDA_ON_AMAZON_PRIME_TV_SHOWS_AND_MOVIES.ipynb
```

Run all cells sequentially.

---

## Future Improvements

- Add interactive dashboards using Plotly or Power BI
- Perform sentiment analysis on movie descriptions
- Build recommendation systems
- Deploy visualizations using Streamlit

---

## Conclusion

This project demonstrates how Exploratory Data Analysis can help understand content trends and patterns in streaming platforms like Amazon Prime Video. The analysis provides insights into genres, production countries, and release trends over time.

---

## Author

Ajay Kumar

GitHub Repository:
https://github.com/userajayak/EDA-PROJECT-ON-AMAZON-PRIME-TV-AND-SHOWS
