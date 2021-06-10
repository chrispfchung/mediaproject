


# Pitching Microsoft What Content to Create in their Studio


## Data
We sent API calls to themoviedb.org and retrieved data on nearly 6000 movies. Data points include, movie title, revenue, budget, genre, and more.
In addition, we scraped IMDB for Academy Award winning movies sorted by box office revenue. We retrieved 500 data points. These movies datapoints also contain names of directors, actors, and the number of their awards.

### What you will find in our repo:
Data collection and preprocessing files:
- Notebooks showing data collection via webscraping and API calls.
- Notebooks also show preprocessing of our data to create new features like weighted ROI and budgets.

*CSV files show our collected data compiled for easier access and subsequent analysis*

## Approach

### Find
- Estimate required budget
- Genres to invest in
- Which directors to hire?
- Which movie stars do we want?
- Best month to release film (highest gross revenue)


When thinking about how much our budget should be, we looked into which genres have a low barrier entry point. 
Horror and Western had significantly lower budgets. Surprisingly, these genres also performed extremely well from a ROI perspective. Not only is it cheap to produce these movies, on average, they also produce higher profits.

<p align="left"> 
<img src="https://github.com/chrispfchung/mediaproject/blob/master/images/genresandweightedROI.png" alt="jupyter" height=450px />
 </p>

### Findings

Adventure's barrier to entry, or budget, was 22 million while Horror or Western movies had 7.4 and 12 million dollar budgets, respectively.
We also saw that Horror and Western movies had a 500% ROI and 340% ROI while all 9 other genres had ROIs less than 250%.
We zoomed into the top 500 academy award winning movies and looked at the top 5 Horror / Western genre directors and actors with the most awards. Our thought is that while you start out your movie studio, these are excellent people to include in your next horror/western movie.

### Top 5 Actors
![top5actors](https://github.com/chrispfchung/mediaproject/blob/master/images/top5actors.png)


Finally we looked at the overall movie release months over the last 100 years, May and June (early summer) and November and December (winter holiday) months had higher revenue compared to the other months. We recommend that you look into these months to release your movie.

<p align="left"> 
<img src="https://github.com/chrispfchung/mediaproject/blob/master/images/grossprofitbymonth.png" alt="jupyter" height=400px />
 </p>



