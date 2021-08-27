# cricket-world-cup2019--k-means-clustering-on-batsmen-data

We will use scrapped players and matches data to implement k-means clustering. For scrapping of data, please refer other repository 
`https://github.com/niteshjindal170988/cricket-world-cup2019--players_data_scrapping`

Scrapped data which is used for clustering can be found here:- 
https://drive.google.com/drive/folders/1IQCUKo1zBkVKM1b9NPMl2EApVb00cpXn?usp=sharing

Clustering the players based on the number of balls faced by them, total runs scored, number of 4s they hit and number of 6s they hit. 

This will render us the group of players who showed similar pattern in their batting style. That is to say, players who hit same number of 4s and 6s and maintained a similar strike rates will create a cluster unqiue to them.

Steps-

1. Load the scrapped 'matches data', Data Preprocessing and extract the required information

2. Data Preprocessing Phase[from scrapped Matches_data.csv]

3. Prepare Batsman data with number of balls played, runs scored, number of 4s hit, number of 6s hit

4. Implement k means clustering - randomly assign centroids and follow expectation-maximization algorithm
