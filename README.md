# README for App Analysis Project

## Overview

This project provides a comprehensive analysis of mobile applications based on their ratings, categories, pricing, and user reviews. The analysis aims to uncover insights into the mobile app market, helping developers and businesses make informed decisions.

## Dependencies

- Python 3.x
- pandas
- numpy
- plotly
- seaborn
- matplotlib

## How to Run

1. Ensure you have the required dependencies installed.
2. Place the dataset `apps.csv` and `user_reviews.csv` in a folder named `datasets`.
3. Run the provided script.

## Project Structure

The script performs the following operations:

1. **Data Loading and Cleaning**:
    - Reads the app dataset and drops duplicate entries.
    - Cleans specific columns by removing unwanted characters.
    - Converts certain columns to the appropriate data types.

2. **Exploratory Data Analysis**:
    - Displays a random sample of the dataset.
    - Visualizes the distribution of apps across categories.
    - Analyzes the distribution of app ratings.
    - Investigates the relationship between app size, price, and ratings.
    - Examines app pricing trends across popular categories.
    - Filters out junk apps priced unreasonably high.

3. **Comparative Analysis**:
    - Compares the number of downloads between paid and free apps.
    - Merges app data with user reviews.
    - Analyzes user sentiment polarity for paid vs. free apps.

## Datasets

- `apps.csv`: Contains detailed information about each app, including its category, rating, price, and more.
- `user_reviews.csv`: Contains user reviews for various apps, including sentiment scores.

## Insights

The analysis provides insights such as:

- Distribution of apps across different categories.
- Average app rating and its distribution.
- Relationship between app size and rating.
- Relationship between app price and rating.
- Pricing trends across popular app categories.
- Download trends for paid vs. free apps.
- User sentiment polarity for paid vs. free apps.

## Contribution

Contributions are welcome! If you have additional analyses or visualizations to suggest, or if you find any issues, please feel free to contribute.

## License

This project is open-source. Please ensure you provide proper attribution if you use or modify the code.
