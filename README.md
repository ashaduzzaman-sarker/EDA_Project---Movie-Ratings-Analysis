# Movie Ratings Analysis

## Overview
This project explores the discrepancy in movie ratings provided by Fandango compared to other review sites. The investigation aims to uncover potential biases in Fandango's ratings system and its implications on moviegoer decision-making.

## Background
The analysis was inspired by an article titled "Be Suspicious Of Online Movie Ratings, Especially Fandango’s" from [FiveThirtyEight](https://fivethirtyeight.com/features/fandango-movies-ratings/), highlighting concerns about Fandango's rating system favoring higher ratings.

## Data Used
- **Fandango Data:** Scraped data of Fandango stars and displayed ratings from `fandango_scrape.csv`.
- **Other Movie Review Sites:** Aggregate data from Rotten Tomatoes, Metacritic, and IMDb obtained from `all_sites_scores.csv`.

## Analysis Steps
### 1. Understanding the Data
- Loaded and examined the Fandango and other review sites' datasets.
- Explored relationships between ratings and votes.

### 2. Fandango Displayed Scores vs. True User Ratings
- Investigated discrepancies between Fandango's displayed stars and actual user ratings.
- Analyzed the distribution of ratings across movies and identified potential biases.

### 3. Comparison to Other Review Sites
- Compared Fandango ratings to those from Rotten Tomatoes, Metacritic, and IMDb.
- Visualized differences in ratings distributions across various platforms.

## Findings
- Fandango's displayed ratings tended to be higher than true user ratings.
- Observed discrepancies suggest a bias towards inflated ratings on Fandango.
- Fandango ratings were notably higher than those on other review sites.

## Conclusion
- Consumers should approach Fandango ratings with caution when making movie choices.
- Further investigation is recommended to understand the reasons behind this bias.

## Future Directions
- Perform statistical tests to quantify the observed biases.
- Investigate the impact of Fandango's high ratings on movie ticket sales.
- Monitor recent data for changes in Fandango's rating practices.
- Explore user reviews and conduct sentiment analysis for deeper insights.

---

Feel free to customize this README file further by adding details about the analysis process, code snippets, or additional findings you might have discovered during your investigation.
