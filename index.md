Billboard Hot 100 has witnessed the rise and fall of various music genres and audio formats in the U.S. since 60+ years ago. Its formula and chart policy have also evolved a lot to maintain its representativeness of the music trend. For example, to keep the chart as current as possible, a song will be permanently moved to "recurrent status" if it has spent 20 weeks on the Hot 100 and fallen below position # 50. Additionally, descending songs are removed from the chart if ranking below # 25 after 52 weeks. However, there are still some complaints that the chart is becoming more and more stagnant. So is there any way to measure the fluidity of the chart? If any, how does the *fluidity* of Billboard Hot 100 change over time? And why do people feel that the chart is becoming more stale? With these three questions in my mind, I started this project.

This project scraped the [Billboard Hot 100 chart](https://www.billboard.com/charts/hot-100) from its very first issue dated Aug 2nd, 1958 to the latest release of Feb 1st, 2020, including the title, the artist, the trend (*New*, *Steady*, *Rising*, or *Failing*), and the specific position change of each song on chart. I first crafted some basic metrics (such as # of *New Entry*s, # of *Steady* songs, and average position change) to measure the *fluidity* of the chart, but found some contradictary evidences to this question. Then I shifted my focus to the top part of the chart (Top 10/Top 40) as the public were more exposed to this info thus this may influence how stagnant they feel the chart was. Several metrics, namely # of songs made it to top 10/top 40, and the distribution of duration on top10/top 40, turned out to be revealing in resolving the contradiction and answering why people found the chart more stagnant. 

**Table of Content**  
[Part I: Get the Data](#part-i-get-the-data)  
[Part II: The *New*s of Hot 100](#part-ii-the-news-of-hot-100)  
[Part III: The *Steady*s of Hot 100](#part-iii-the-steadys-of-hot-100)  
[Part IV: The *Rise*s and *Fail*s](#part-iv-the-rises-and-fails)  
[Part V: The *Tenure* of Songs](#part-v-the-tenure-of-songs)

## Part I: Get the Data
Two *Python* libs were employed to scraped the [Billboard Hot 100 chart](https://www.billboard.com/charts/hot-100) history: *requests* and *bs4* (BeautifulSoup). To avoid being blocked by Billboard website, I set up a 5 seconds sleep time between each visit and let the script run for a whole night. The final data consisted of three datasets: title_df contained the title and artist info, change_df stored the position change info, and trend_df tracked the trend info (*New*, *Steady*, *Rising*, or *Failing*). Each dataset had 3210 columns and 100 rows (weekly Hot 100 from Aug 2nd, 1958 to Feb 1st, 2020). Below are the screenshots of the title_df, change_df, and trend_df, respectively.

![Title_df Screenshot](/visuals/title_df_head.png)  
![Change_df Screenshot](/visuals/change_df_head.png)  
![Trend_df Screenshot](/visuals/trend_df_head.png)  

## Part II: The *New*s of Hot 100

## Part III: The *Steady*s of Hot 100

## Part IV: The *Rise*s and *Fail*s.

## Part V: The *Tenure* of Songs

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://y-hang.github.io/TS-Lyrics-Analysis/images/uniqueness_by_song.html" height="450" width="1000"></iframe>