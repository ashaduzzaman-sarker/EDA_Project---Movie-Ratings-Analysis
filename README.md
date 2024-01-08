# Fandango Movie Ratings Analysis

## Overview

When deciding which movie to watch, online reviews and ratings play a crucial role. This project investigates the potential bias in Fandango's movie ratings in 2015 and explores the relationship between Fandango ratings and true user ratings. Additionally, it compares Fandango ratings to other movie review sites (Rotten Tomatoes, Metacritic, and IMDb) and examines the distribution of ratings across platforms.

## Data Sources

- **Fandango Data:** The analysis utilizes the `fandango_scrape.csv` file, containing Fandango stars and displayed ratings.
- **Other Movie Review Sites Data:** The `all_sites_scores.csv` file provides aggregate data from other movie review sites, including Rotten Tomatoes, Metacritic, and IMDb.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/movie-ratings-analysis.git
   cd movie-ratings-analysis
   ```

2. **Install Dependencies:**
   Ensure you have the required libraries installed:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```

3. **Run the Jupyter Notebook:**
   Open the Jupyter Notebook in your preferred environment:
   ```bash
   jupyter notebook Movie_Ratings_Analysis.ipynb
   ```
   Execute the cells step by step to reproduce the analysis.

## Findings

### Part One: Understanding the Background and Data
- Read the relevant article to understand the motivation behind the analysis.
- Explored the Fandango dataset, including the distribution of ratings and the relationship between rating and voting.

### Part Two: Exploring Fandango Displayed Scores versus True User Ratings
- Investigated the potential bias by comparing displayed stars (`STARS`) with true user ratings (`RATING`).
- Explored the distribution of ratings and identified movies with a significant difference between displayed stars and true user ratings.

### Part Three: Comparison to Fandango Ratings to Other Sites
- Loaded and explored data from other movie review sites (Rotten Tomatoes, Metacritic, IMDb).
- Compared Fandango ratings with those from other platforms, highlighting potential biases.

### Part Four: Summary and Conclusion
- Summarized key findings, emphasizing the observed biases in Fandango's ratings.
- Provided recommendations for users and suggested potential future steps for analysis.

## Future Steps
- Perform statistical tests to quantify observed biases.
- Investigate the impact of Fandango's high ratings on movie ticket sales.
- Monitor recent data to see if Fandango has made any changes since 2015.
- Explore user reviews and comments to understand the qualitative aspects of the bias.
- Consider conducting sentiment analysis on user reviews for additional insights.

Feel free to explore and contribute to the analysis! If you have any questions or suggestions, please open an issue or reach out to the project contributors.
