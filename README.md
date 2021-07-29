# Final Ironhack Project

<p align="center">
  <img src="https://github.com/aranaxa/Ironhack-Final-Project/blob/main/Images/movies.png" />
</p>

## Movie Finder Dashboard for _MovIndie_

Axana Raiser, Data Analytics Bootcamp, July 2021

#### Content

1. [Description](https://github.com/aranaxa/Ironhack-Final-Project/blob/main/README.md#description)
2. [Process and Tools](https://github.com/aranaxa/Ironhack-Final-Project/blob/main/README.md#process-and-tools)
3. [Data Sources](https://github.com/aranaxa/Ironhack-Final-Project/blob/main/README.md#data-sources)
4. [Dashboard and Presentation](https://github.com/aranaxa/Ironhack-Final-Project/blob/main/README.md#dashboard-and-presentation)

## 1. Description

The (imaginary) movie streaming platform _MovIndie_ needs help! The company is renown for their handpicked selection of independent movies available for streaming on their website, but due to the ever-growing number of movie releases, it’s becoming more and more time-consuming for the small team to make noteworthy picks. In order to simplify this process, they would like to use an interactive tool that can help in the pre-selection process of their movies. 

This project involves web scraping, using different APIs, cleaning and analyzing all the data, and finally creating a dashboard that can be filtered by multiple metrics (genre, director, language, keyword etc.) to serve the company's purpose.

## 2. Data Sources

<img src="https://github.com/aranaxa/Ironhack-Final-Project/blob/main/Images/imdb.png" width="120"/>
IMDb is the largest online movie database including information on half a million movies. To find movies relevant for this project, I have initially scraped the website for ~20,000 movies. Further filtering (i.e. removing movies by major production companies) have resulted in a dataset of ~15,000 movies. To store all relevant movie details, I have used the following unofficial IMDb APIs (via RapidAPI):


- [Movie Database (IMDB Alternative)](https://rapidapi.com/rapidapi/api/movie-database-imdb-alternative/1)
- [Data-Imdb](https://rapidapi.com/SAdrian/api/data-imdb1/)
- [SERIES-MOVIES-IMDB](https://rapidapi.com/chrisish71/api/series-movies-imdb/)

___
<img src="https://github.com/aranaxa/Ironhack-Final-Project/blob/main/Images/tmdb.png" width="120"/>

To complement the data gathered via IMDb, I have used [TMDb's official API](https://www.themoviedb.org/documentation/api) to gather more details on keywords and gender of actors and directors.

The final dataset contains ~10,000 after removing missing content.

## 3. Process and Tools

- Outline project and define goals
- Research data sources
- Set up project environment (GitHub repository, [Trello Kanban board](https://trello.com/b/JvgHkH9q/ironhack-final-project))
- Gather data via web scraping and APIs
- EDA, clean and wrangle data in Python and Pandas
- Analysis and visualization in Tableau
- Create interactive dashboard in Tableau
- Presentation with Google Slides

### 4. Dashboard and Presentation

To view the dashboard, please click [here](https://public.tableau.com/app/profile/axana.r/viz/IronhackFinalProject_16275850352720/Dashboard?publish=yes). 
The presentation slides can be found [here](https://docs.google.com/presentation/d/1xuf8jtm_vtRjyJ4kgdJOjFOXGxOYD_WEO4tmbj1G8yc/edit?usp=sharing).

__________

Thank you for reading! Feel free to reach out to me in case of any questions.
