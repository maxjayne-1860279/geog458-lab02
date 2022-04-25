# geog458-lab02

## Introduction

In this lab, tweets are gathered using a python crawler and twitter's API. The tweets are then plotted on a map for geographic examination and their text plotted to word clouds to further analyze tweet content.
The tweets gathered in this lab all mention the keyword 'Ukraine' in an effort to gather geospatial data on public discourse surrounding the Russian invasion of the Ukraine. Tweets were gathered at 10 am PST and again at 4pm PST for comparison. For both tweet sets the crawler was run for 30 minutes, and filtered out non-english tweets. The primary method of analysis will be comparing the two sets taken at different times both to capture tweets from the US and Europe (7 hr time difference) and to compare between the two regions using time as a mild division. Furthermore, the two different times may give insight as to how public sentiment changes throughout the day. If it were possible, a direct comparison between two regions would also prove very informative, however geographic bounds cannot be set easily while also filtering for a keyword when gathering tweets.

***

## Maps

![A map displaying tweets (morning)](/imgs/geotweets-1.png)

![A map displaying tweets (afternoon)](/imgs/geotweets-2.png)

The two maps above visualize the gathered tweets mentioning the Ukraine. When comparing the geographic distribution of the two tweet sets, we can see that there are more tweets from Europe in the morning subset, likely due to the time difference, where the 10 am sample would equate to a 5pm sample. Both maps feature the majority of tweets originating from the US, most from the East coast. This is likely due to the popularity of twitter in the US, as well as the prominence of English. Another notable difference is that the afternoon sample features tweets from Africa and Australia, as well as Europe, many of which would have had to have been posted late in the evening. We can tell from these geographic distributions that people around the world are tweeting about the Russian invasion of Ukraine at all times of the day. The differences in distribution are slight and are most likely a result of the time difference.

***

## Word Clouds

![A wordcloud from morning tweets](/imgs/wordcloud1.jpeg)

![A wordcloud from afternoon tweets](/imgs/wordcloud2.jpeg)

The two word clouds display the most common words found in the respective twitter crawls (the larger the word on the word cloud the more occurrenes were found in the associated tweets). The primary context for comparison is on the basis that more European english speaking twitter users may be active in the morning set of tweets where time is 7 hours later. When comparing the two, we can see that there are notably more American and religious terms such as "Christian", "Republican", and "Biden" mentioned in the morning group of tweets, despite the later group of tweets having more tweets actually originating from the US (assuming no VPN usage or other locational spoofing). Both groups feature many words relating to the inavasion such as "war" and "defend", and some such as "stop" and "help" show the tension and despair present as a result of the invasion. Overall the two feature very similar themes revolving around the war.