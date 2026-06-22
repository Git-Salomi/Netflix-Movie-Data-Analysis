# Netflix-Movie-Data-Analysis (Exploratory Data Analysis using Python)
## Project Objective
To explore a dataset of movies and uncover patterns in genre popularity, audience ratings, and release trends — helping understand what kind of content performs best and when most movies are released.
## Dataset used
- <a href="https://github.com/Git-Salomi/Netflix-Movie-Data-Analysis/blob/main/mymoviedb.csv">Dataset</a>
## Questions (KPIs)
- What is the most frequent genre in the dataset?
- Which genre has the highest audience votes?
- Which movie got the highest popularity? What's its genre?
- Which movie got the lowest popularity? What's its genre?
- Which year has the most filmed movies?
- Notebook <a href="https://github.com/Git-Salomi/Netflix-Movie-Data-Analysis/blob/main/Netflix_Movie_Data_Analysis.ipynb">View Notebook</a>
## Process
- Verified data for missing values and duplicates (none found).
- Converted Release_Date to datetime and extracted release year.
- Dropped low-value columns for analysis: Overview, Original_Language, Poster_Url.
- Categorized Vote_Average into four bins — not_popular, below_avg, average, popular — using quartile-based cutoffs.
- Split and exploded the Genre column (originally comma-separated) so each row represents a single movie-genre pair.
- Visualized genre distribution, vote distribution, and release year trends using Matplotlib and Seaborn.
## Project Insight
- Drama is the most frequent genre, appearing in over 14% of entries across 19 genres.
- 25.5% of the dataset (6,520 rows) falls into the "popular" vote category, with Drama again leading at over 18.5% of popular titles.
- Spider-Man: No Way Home recorded the highest popularity score, spanning the Action, Adventure and Science Fiction genres.
- 2020 was the most prolific year for movie releases in the dataset.
## Final Conclusion:
Drama stands out as the genre that consistently drives both volume and audience engagement, making it the safest bet for content strategy. With movie output peaking in 2020 and popularity skewed toward a small set of high-performing titles, content platforms should prioritize Drama-led releases while using popularity outliers like Spider-Man: No Way Home as benchmarks for what drives breakout audience attention.
