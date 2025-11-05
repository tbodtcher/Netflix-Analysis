# Netflix-Analysis

Netflix Titles: An Exploritory Data Analysis
Purpose The purpose of this exploritory data analysis (EDA) is to gain insights into this dataset, using my skills I have learned in Python. I will be attempting to discover common trends in genres, ratings, duration, and much more.

This data comes from a publicly avaliable dataset from Kaggle. ( https://www.kaggle.com/datasets/shivamb/netflix-shows )

To begin, let's import the data and take a look at the first few rows to see how the data is formatted. We also can try to see if there will be any problems with duplicate or missing values.

Looking at the first few rows of data, we can see that it is actually a very well formatted dataset. Data is clean, and clear to read. However, I want to check to make sure that we do not have any duplicate values, before I go into more detail.

In the code above, I was able to indentify that there were no duplicate values. The code went through each row and tried to find rows that had the same "Show ID" and "Title". It found no rows, so I feel confident in saying that there are no duplicated values.

However, we can see that we do have some null values in our dataset, in various rows. Because we will be performing analysis functions on a variety of columns in this dataset, my decision will be to keep the rows will null values, but make note of them going forward. I believe the rest of the data in the rows are worth having.

Moving on to the actual analysis of our EDA, I want to start by looking at the summary statistics for our "Release Year" column. Movies have been made for a long time now, and I'm curious to see what the average release year and median release year are for this dataset. I know Netflix hasnt been around for long, but I know they have an impressive range of titles in their library.

My hypothesis is that the average release year will be in the mid-2000's (2005). I think this because of the large quantity of "Classic" movies that came out before then.

After looking at the results of my code, I can see that the average release year for the titles in the dataset is 2014. While this is fairly close, my hypothesis is incorrect. The average year is a lot closer to today than I thought. This could be because of the high quantity of Netflix-made filmes and tv shows that Netflix is releasing.

Next, I want to see the most common ratings for both movies and tv shows. Again, I know that Netflix has a wide range of things to watch, so I am curious to see how the ratings are broken down for movies and TV shows.

After viewing the results of my code, I was surprised to see that not all of the movie titles followed the traditional rating system. There were a lot of movies that had the TV-style ratings (TV-MA, TV-14, etc.). Upon further reasearch, I found that Netflix has started incorporating tv ratings with the goal of having more generic ratings across different countries that make films, along with standardizing ratings to help parents decide what their children can watch.

With that being said, the rating with the highest number of movies listed is TV-MA, with 2062 titles. For traditional movie ratings, R rated has the highest number of titles, with 797.

Now, let's look at TV shows.

TV shows follows movies, with TV-MA having the most titles at 1145. This result makes since as Netflix has been focusing a lot of their TV shows as documentary-style shows about serial killers and violent historical occurences.

Overall, I am a bit surprised at the amount of mature movies and tv shows that Netflix offers.

Continuing the thought process of high numbers of mature rated titles, let's look into the genres listed for each title, and try to find out which one is the most common. If I am right, the top genres should be associated with dramatic themes.

Something to note is that this dataset does not list genres explicitly, they are categorized into the column "Listed In". This is in reference to the sections of the Netflix platform that people can look in to find titles that related to that topic.

The top 3 "Listed In" categories are "International Movies" - 2752 mentions, 'Dramas' - 2427 mentions, and 'Comedies' - 1674 movies.

Because we do not have direct genres, the international category has the most mentions. However, if we look for the first "Genre" category, it is Drama. This makes sense with the higher ratings, and confirms what I thought after our analysis of ratings.

Moving onto visualizations, I first made a pie chart that shows the breakdown of movies and tv shows as part of a whole. Out of our entire dataset, movies represent 69.6% of our data, while 30.4% of the data comes from TV Shows.

This visualization is a histogram that shows the distribution of release year of the titles that we have from this dataset. As we can see, most of the titles that Netflix has on their platform were released after 2010. This explains why the average release year from earlier was so high!

Finally, this bar plot shows the top 5 countries with titles in Netflix. The United States has by far the most titles in this dataset, with over double the next highest country.

This does not surprise me since Netflix is Headquartered in the United States, so it makes sense that they would have the most amount of titles come from that company.

Conclusion
After completing this EDA on the dataset of Netflix titles, I can say that I have a deeper understanding of the types of titles that Netflix carries, according to this dataset. Together, we learned that most of the titles that Netflix carries come from more modern times, and of those titles, most of them are maturely rated.

We looked at clear visualizations, and gained important insights into the data with pie charts, histograms, and bar plots.

Overall, this analysis has reaffirmed my knowledge that Netflix carries a vast library of titles, with different types of titles that would fit almost anyones needs for a relaxing streaming platform.
