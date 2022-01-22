# Movie success based on  genre rating and Return on Investment


## Background
Every Year, different movies of different genres are released every year. This project analyzes the success of different genres 
and their average return on investment percentage. Using the top genres with highest value counts, I analyze descriptive statistics for both average rating and and return on investment percentage.

## Business Problem
When movies are analyzed for their success, they analyze individually how well that single movie does. There is no real analysis for success of specific genres. Are Specific genres more prone to success than others? Using the genres with the highest value counts for statiscal accuracy, analysis of average rating and their return on investments for specific genres.

## Data
Using three different data sets, that contain similar columns but different data I merge them to get a clear picture of everything. These data sets are average rating, movies and genres, and movies  with budgets/gross data. I merge these data sets to get a complete picture of everything which is used for analysis. Since Return on Invesment also needs to be calculated, the budget and gross are converted to integers for mathematical analysis.

## Methods
Using valiue counts to determine the top 5 genres with the highest value counts. We create seperate dataframes that specfically target those genres to use for analysis. I used those genres to perform descriptive statistics on both average rating and the return on investment percentage. 
I also provide basic descriptive statistics for the other movies with lower value counts, to share their data. With the top genres I also graphed the Return on Investment and Average to see if their correlation.

## Results
Results show there is a general increase in Return on Investment as predicted. Unexpected results, show outliers on the higher return on investment but they do not appear on the higher average ratings rather the middle section of average ratings.


## Conclusions
In conclusion,the genre Drama has the highest average rating and highest return on investment while comedy/drama has both lowest average rating and lowest return on investment. Dramas will almost always receive great ratings and and a high return on investment.


## Next Steps 

 #### How can we increase ROI Percentage?
 Could Having potential more popular studios, directors, writers play a major role in movie success and overall?
 #### More Data in other Genres
 Low Data data for other genres not mentioned such as Action, Fantasy, Horror. More Data is needed to perform analysis on their success  
 #### Different measure of success
Rather than measure Return on Investment percentage and average rating. Meaure average rating of success of certain directors in movie genres and compare how similar directors that work in that genre do