# Netflix Movies and TV Shows EDA

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg)

## Overview

This project provides an exploratory data analysis (EDA) of a comprehensive dataset of movies and TV shows available on Netflix. The analysis covers various aspects such as content distribution, genre popularity, temporal trends, and insights into directors and actors.

## Dataset

The dataset used in this project is a comprehensive compilation of movies and TV shows available on Netflix, as of mid-2021. It includes vital details such as cast, directors, ratings, release year, duration, and more.

**Dataset Features:**

- `show_id`: Unique identifier for each title
- `type`: Category of the title (Movie or TV Show)
- `title`: Name of the movie or TV show
- `director`: Director(s) of the title
- `cast`: Main actors/actresses in the title
- `country`: Country where the movie or TV show was produced
- `date_added`: Date the title was added to Netflix
- `release_year`: Year the movie or TV show was released
- `rating`: Age rating of the title
- `duration`: Duration of the title (in minutes for movies and seasons for TV shows)
- `listed_in`: Genres the title falls under
- `description`: Brief summary of the title

## Analysis and Visualizations

### Data Cleaning and Preparation

- Filled missing values in 'director' and 'cast' columns with 'Unknown'.
- Standardized the 'date_added' column to a consistent datetime format.
- Converted the 'duration' column to numeric values.
- Replaced infinite values with NaN.

### Key Insights

1. **Content Distribution by Release Year**: Visualization of the distribution of content release years.
2. **Count of Movies vs TV Shows**: Comparison of the number of movies and TV shows.
3. **Genre Popularity**: Word cloud and bar chart of the most common genres.
4. **Content Distribution by Country**: Map visualization of the number of titles produced by each country.
5. **Age Ratings Distribution**: Pie chart showing the distribution of age ratings.
6. **Movie Durations**: Box plot of movie durations.
7. **Temporal Trends**: Analysis of the number of titles added each year.
8. **Non-US Content Growth**: Visualization of the growth of non-US content on Netflix.
9. **Top Directors and Actors**: Bar charts of the most prolific directors and actors.
10. **Movie Duration and Rating**: Analysis of the relationship between movie duration and rating.
11. **Genre Duration Comparison**: Box plots comparing movie durations and TV show seasons across genres.

### Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- wordcloud
- plotly
- geopandas

## How to Run the Code

1. **Clone the repository**:
    ```sh
    git clone https://github.com/dor851997/EDA-of-the-Netflix-Movies-and-TV-Shows-dataset.git
    cd netflix-movies-tvshows-eda
    ```

2. **Install the required libraries**:
    ```sh
    pip install pandas numpy matplotlib seaborn wordcloud plotly geopandas
    ```

3. **Run the Jupyter Notebook**:
    Open `netflix_eda.ipynb` in Jupyter Notebook or Jupyter Lab and run the cells to see the analysis and visualizations.

## Results

The cleaned dataset is saved as `cleaned_netflix_titles.csv`. You can find the visualizations and insights in the Jupyter Notebook `netflix_eda.ipynb`.

## Contributing

Contributions are welcome! Please open an issue to discuss what you would like to change or add.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset was sourced from [Kaggle](https://www.kaggle.com/shivamb/netflix-shows).
- Special thanks to the open-source community for providing excellent tools for data analysis and visualization.
