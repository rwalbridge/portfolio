# Analysis of Pitchfork Album Reviews & Billboard Hot 100 Rankings (by Artist)
[Pitchfork.com](https://pitchfork.com/) is one of the most respected opinions in the music industry when it comes to measuring how "good" an artist, album or song is. The [Billboard Hot 100](https://www.billboard.com/charts/hot-100/) is the most widely accepted ranking of song popularity in the US, updated weekly.

## Goal of the Project
I wanted to find out what artists fell into a so-called "sweet spot" of high Pitchfork ratings AND high Billboard ratings. At the same time, I also wanted to confirm the widely accepted belief that Pitchfork does NOT adhere to mainstream popularity and identify where Pitchfork typically ranks mainstream artists.

## Overview of Datasets
- #1 : Pitchfork Web Scraping Dataset (Album Reviews: 2017-2021)
> This was started as part of an earlier project to analyze just the Pitchfork album review data alone, which I developed a web scraping program for to capture the following variables for all album review pages: artist name, album name, album year, record label, and album rating. Originally I developed this to scrape all 2,000+ pages, but the processing time was too long. So after finding the Kaggle dataset (below), I edited this code to run only for missing years from 2017-2021.
- #2 : Pitchfork Kaggle Dataset (Album Review: 1999-2017)
> This dataset was available on [Kaggle](https://www.kaggle.com/ermoore/pitchfork-reviews-through-12617) and was scraped similar to my method above. This contained all webpages up to 2017 (when the dataset was created) and included variables for: artist name, album name, date added, genre, review text and album rating.
- #3 : Billboard Hot 100 Dataset (Weekly Rankings, All-Time)
> This dataset was also availale on [Kaggle](https://www.kaggle.com/dhruvildave/billboard-the-hot-100-songs) and was made available through web scraping. It contains weekly rankings of the Hot 100 for all-time and includes variabls for: week, song title, artist name, song rank, song peak rank, and total weeks on board.
 
## Overview Presentation
[HERE](https://docs.google.com/presentation/d/19rOHQMwOvZpOgMOY2N7vdHYraxkoKY7_UiKmNT6DXb8/edit?usp=sharing) is a link to my presentation explaining the analysis, showing the visualizations, and describing key findings.

## Info
Made as part of [Nod Coding Bootcamp](https://www.nodcoding.com/) #4 2021
