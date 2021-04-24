## Dataset Description ##

With every match Dota 2 is creating a replay file, where all the actions, locations, chats and stats are logged. With this file a match can be replayed and analyzed in the Dota 2 client itself, or can be downloaded and parsed with user-created java or c++ libraries [[1]]. Additionally there are several websites [[2]][[3]] that parse and analyze competitive and or ranked matches, offer tools to analyze own and others matches, and with this create some meta stats about heroes, best builds and so on.

Since this research is about the influence of popular, repeated and successful combinations of hero actions on the patches, the replay-files are needed to extract the match-logs and further the hero actions and their stats.

### Scraping Data ###
To get the competitive matches and the Urls of the replay-files i scraped *datdotas* archives through their API and got 32072 matches from 207 tournaments between 2015 and the beginning of April of 2021, when the latest patch 7.29 was published. I choose not to go later than patch 6.85 because in the summer of 2015 Dota 2 was ported to Valves Source 2 graphic engine, and with that also the replay files framework changed. 

![Dataset-Match-Distributions][img1]

#### Dataset Patch Statistics ####
This is the initial list of matches i got from scraping *datdota*. The patch statistics are quite irregular. Starting from the pure amount of matches, the time span between the updates, the mean games per game days and insofar the match intensity within a patch. This also comes from a trial go away from major to more regularly minor Patches between the beginning of 2017 and and mid 2018. This can be seen in the lower match numbers in this Update circles.

```
		            		matches	                       days
		                	 sum  mean   std  max

	   patch 		date                               
		6.85  2015-09-24    1622  19.5  12.4   82
		6.86  2015-12-16    2453  19.2  15.5  130
		6.87  2016-04-25    1449  32.9  41.7   45
		6.88  2016-06-12    3524  22.2  15.8  182
		7.00  2016-12-13     173  21.6  11.3    7
		7.01  2016-12-20     652  15.5  15.5   44
		7.02  2017-02-08     455  21.7  31.9   34
		7.03  2017-03-15     149  18.6   5.4    7
		7.04  2017-03-23     241  16.1   8.9   16
		7.05  2017-04-09     768  22.6  11.2   35
		7.06  2017-05-15    2176  18.9  19.9  168
		7.07  2017-10-31    1632  20.7  19.0   92
		7.08  2018-02-01     452  32.3  17.7   13
		7.09  2018-02-15     183  13.1   5.2   13
		7.10  2018-03-01     196  14.0  14.4   13
		7.11  2018-03-15     428  30.6  22.5   14
		7.12  2018-03-29     215  15.4   8.8   13
		7.13  2018-04-12     285  21.9  17.2   13
		7.14  2018-04-26     122  11.1   4.6   13
		7.15  2018-05-10     179  13.8   8.9   16
		7.16  2018-05-27     103  12.9   6.6    8
		7.17  2018-06-10     247  24.7  16.8   15
		7.18  2018-06-25     130   6.5   2.3   34
		7.19  2018-07-29    1176  17.3  15.3   95
		7.20  2018-11-19     684  15.5  13.6   69
		7.21  2019-01-29    1968  20.9  19.6  115
		7.22  2019-05-24    1866  15.8  17.2  183
		7.23  2019-11-26     696  17.4  26.2   56
		7.24  2020-01-26     603  18.8  22.7   42
		7.25  2020-03-17     616  20.5  10.3   33
		7.26  2020-04-17    1587  21.4   8.3   73
		7.27  2020-06-28    3304  19.3   8.4  171
		7.28  2020-12-18    1712  17.0   9.2  113
		7.29  2021-04-09      26   6.5   4.7    3
```



[1]:https://github.com/skadistats/clarity

[2]:https://www.dotabuff.com/esports/matches
[3]:https://www.opendota.com/matches
[4]:https://www.datdota.com/
[5]:https://www.dota2.com/reborn/part1

