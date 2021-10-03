# Beer Data Challenge

## Dataset

This repository explores the beer dataset containing the following columns. 

- beer_ABV	
- beer_beerId	
- beer_brewerId	
- beer_name	
- beer_style	
- review_appearance	
- review_palette	
- review_overall	
- review_taste	
- review_profileName	
- review_aroma	
- review_text	
- review_time

## Questions 

1.	Rank top 3 Breweries which produce the strongest beers?
2.	Which year did beers enjoy the highest ratings? 
3.	Based on the user’s ratings which factors are important among taste, aroma, appearance, and palette?
4.	If you were to recommend 3 beers to your friends based on this data which ones will you recommend?
5.	Which Beer style seems to be the favorite based on reviews written by users? 
6.	How does written review compare to overall review score for the beer styles?
7.	How do find similar beer drinkers by using written reviews only?   

## Setup
The dataset can be downloaded from 
https://drive.google.com/open?id=1e-kyoB97a5tnE7X4T4Es4FHi4g6Trefq

Unzip the file and you should see a CSV file, called “BeerDataScienceProject.csv”

Since the computation can take a great amount of time, precomputed result can be found at
https://drive.google.com/drive/folders/1_XWkIJoTmtdDVJH1iFuyygPoJLwevbS4?usp=sharing

- "df_sentimental.csv" contains the dataframe with polarity score from sentiment analysis needed for question 5 and 6. The computation was done using the entire written reviews from “BeerDataScienceProject.csv”.
- "df_similar_drinker.csv" contains the dataframe with encoded numerical vector representation of written reviews needed for question 7. The computation was done using 10,000 samples of written reviews from “BeerDataScienceProject.csv”. 

Please download all the mentioned files and put in a folder named "dataset". 
