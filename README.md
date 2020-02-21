# Billboard-Hot-100-Fluidity-Analysis
If you have not been living under a rock, you should have heard of the one of the biggest hits in 2019, Old Town Road, which topped the Billboard Hot 100 for a record-breaking 19 weeks. However, 19 weeks with the same song on # 1 could also be a headache for Billboard Hot 100: a stagnant chart would wear on audience's interests. So in its 60+ years' history, Billboard Hot 100 has also updated its formula and chart policy a lot to balance the representativeness of music trend and the fluidity of the chart. For example, to relieve the stagnancy caused by the integration of SoundScan and BDS (Broadcast Data System) data in 1990s, Billboard established a new removal policy that a song will be permanently moved to 'recurrent status' if it has spent 20 weeks in the Hot 100 and fallen below position # 50. In the last decade, the policy was extended to remove descending songs ranking below # 25 after 52 weeks. However, even after these attempts to stimulate and re-activate the chart, there are still some complaints that the chart is becoming stagnant. So is there any way to measure the fluidity of the chart? If any, how does the fluidity of Billboard Hot 100 change over time? And why do people feel that the chart is becoming more stale? With these three questions in my mind, I started this mini project out of curiosity.

This project scraped the Billboard Hot 100 chart from its very first issue dated Aug 2nd, 1958 to the recent release of Feb 1st, 2020, including the title, the artist, the trend (New, Steady, Rising, or Failing), and the specific position change of each song in chart. I first crafted some basic metrics (such as # of New Entrys, # of Steady songs, and average position change) to measure the fluidity of the chart, but found some contradictory evidences. Then I shifted my focus to the top part of the chart (Top 10/Top 40) as it had more public exposure thus may influence how stagnant people felt the chart was. In this process, several indicators, namely # of songs made it to top 10/top 40, and the distribution of duration in top 10/top 40, turned out to be helpful in resolving the contradiction and revealing why people found the chart stale in recent years.

The full report is still under construction, and you can visit [here](https://y-hang.github.io/Billboard-Hot-100-Fluidity-Analysis/) to take a look.
