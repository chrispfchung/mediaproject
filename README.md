


# Pitching Microsoft What Content to Create in their New Studio (Hypothetical)


## Data

Data was sourced from two places: The Movie Database API and web scraping IMDB. The API calls to themoviedb.org retrieved data on nearly 6000 movies. Data points included movie title, revenue, budget, genre, and more. We also scraped IMDB for 500 Academy Award winning movies. These movie data points included names of directors, actors, revenue, and more.

### What you will find in our repo:
Data collection and preprocessing files:
- Notebooks showing data collection via webscraping and API calls.
- Notebooks showing data preprocessing to create new features like weighted ROI and budgets.

*CSV files show our collected data compiled for easier access and subsequent analysis*

## Approach

### Find
- Estimate required budget
- Genres to invest in
- Which directors to hire?
- Which movie stars do we want?
- Best month to release film (highest gross revenue)


When thinking about how much our budget should be, we looked into genres with a lower barrier entry point than other ones. 
Horror and Western had significantly lower budgets. Surprisingly, these genres also performed extremely well from an ROI perspective. We found that on average not only was it cheaper to produce these movies, they also produced higher profits.

<p align="left"> 
<img src="https://github.com/chrispfchung/mediaproject/blob/master/images/genresandweightedROI.png" alt="jupyter" height=450px />
 </p>

### Findings

Adventure's budget was 22 million while Horror or Western movies had 7.4 and 12 million dollar budgets, respectively.
We saw that Horror and Western movies had a 500% ROI and 340% ROI while all 9 other genres had ROIs less than 250%.
Following this insight, we zoomed into the top 500 academy award winning movies and looked at the top 5 Horror and Western genre directors, and actors with the most awards. Our thought is that while Microsoft starts out in their studio, these are potential people to include in their next horror/western movie.

### Top 5 Actors
![top5actors](https://github.com/chrispfchung/mediaproject/blob/master/images/top5actors.png)


Finally we looked at the overall movie release months over the last 100 years. Historicall, Early summer (May and June) and Winter Holiday Season (November and December) both had higher revenue compared to other times of the year. We recommend that they look into these months to release their movie.

<p align="left"> 
<img src="https://github.com/chrispfchung/mediaproject/blob/master/images/grossprofitbymonth.png" alt="jupyter" height=400px />
 </p>

