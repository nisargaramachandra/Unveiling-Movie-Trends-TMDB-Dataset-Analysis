 # **Unveiling Movie Trends: TMDB Dataset Analysis**  

This project analyzes over 9,000 movies extracted from the TMDB API to uncover fascinating trends and insights related to genres, popularity, votes, and release patterns.  

## Dataset  

The dataset includes the following key features:  
- **Release_Date**: Date of movie release.  
- **Title**: Name of the movie.  
- **Popularity**: Metric computed by TMDB developers based on views, votes, and other factors.  
- **Vote_Count**: Total votes received.  
- **Vote_Average**: Average rating (out of 10).  
- **Genre**: Classification category for the movie.  

The cleaned dataset contains **6 columns** and **25,551 rows** after preprocessing.  

## Key Questions Addressed  

1. What is the most frequent genre in the dataset?  
2. Which genre has the highest votes?  
3. What movie has the highest popularity? What are its genres?  
4. Which year has the most movies released?  

## Insights  

- **Most Frequent Genre**: Drama is the most common genre, appearing in **14%** of movies.  
- **Highest Votes**: Drama leads with **18.5%** of highly voted movies.  
- **Movie with Highest Popularity**: *Spider-Man: No Way Home* (Genres: Action, Adventure, Science Fiction).  
- **Year with Most Movies Released**: 2020.  

## Tools and Libraries  

- **JupyterLab**  
- **Python 3**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  

## How to Run  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/nisargaramachandra/Unveiling-Movie-Trends-TMDB-Dataset-Analysis.git
   cd movies-dataset-analysis  
   ```  

2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. Open the Jupyter Notebook:  
   ```bash  
   jupyter notebook  
   ```  

4. Run the analysis notebook to explore trends and insights.  

## Data Visualization  

This project uses **Matplotlib** and **Seaborn** for:  
- Genre distribution.  
- Popularity trends over time.  
- Votes by genre.  
- Year-wise trends in movie releases.  

## Acknowledgments  

- Data Source: [TMDB API](https://www.themoviedb.org/documentation/api)  
- Dataset Hosting: [Kaggle](https://www.kaggle.com/)  
