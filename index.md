# Billboard Hot 100 Fluidity Analysis
Billboard Hot 100 has witnessed the rise and fall of various music genres and audio formats in the U.S. since 60+ years ago. Its formula and chart policy have also evolved a lot to keep up with the structural changes in the music industry and maintain its representativeness of the music trend. For example, to keep the chart as current as possible, a song will be permanently moved to "recurrent status" if it has spent 20 weeks on the Hot 100 and fallen below position # 50. Additionally, descending songs are removed from the chart if ranking below # 25 after 52 weeks. However, there are still some complaints that the chart is becoming more and more stagnant. So is there any way to measure the fluidity of the chart? If any, how does the *fluidity* of Billboard Hot 100 change over time? And why do people feel that the chart is becoming more stale?

This project scraped the [Billboard Hot 100 chart](https://www.billboard.com/charts/hot-100) from its very first issue dated Aug 2nd, 1958 to the chart of Feb 1st, 2020, including the title, the artist, the trend (*New*, *Steady*, *Rising*, or *Failing*), and the specific position change of each song on chart. I first crafted some basic metrics (such as # of *New Entry*s, # of *Steady* songs, and average position change) to measure the *fluidity* of the chart, but found some contradictary evidences to this question. Then I shifted my focus to the top part of the chart (Top 10/Top 40) as the public were more exposed to this info thus this may influence how stagnant they feel the chart was. Several metrics, namely # of songs made it to top 10/top 40, and the distribution of weeks on top10/top 40, turned out to be revealing in resolving the contradiction and answering why people found the chart more stagnant. 

Table of Content  
[Part I: Get the Data](#part-i-get-the-data)
[Part II: The *New*s of Hot 100](#part-ii-the-news-of-hot-100)
[Part III: The *Steady*s of Hot 100](#part-iii-the-steadys-of-hot-100)
[Part IV: The *Rise*s and *Fail*s](#part-iv-the-rises-and-fails)
[Part V: The *Tenure* of Songs](#part-v-the-tenure-of-songs)

## Part I: Get the Data

## Part II: The *New*s of Hot 100

## Part III: The *Steady*s of Hot 100

## Part II: The *Rise*s and *Fail*s.

##  Part II: The *Tenure* of Songs

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://y-hang.github.io/TS-Lyrics-Analysis/images/uniqueness_by_song.html" height="450" width="1000"></iframe>