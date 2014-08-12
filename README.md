#Sentiment Analysis on Twitter

###Summary
> Based on a sample of data collected from Twitter API Version 1.1, a sentiment analysis was performed over the selected topic, "obama", using the lexical affinity approach. As a result, the average sentiment scores grouped by states across the U.S. and the states scoring the higest and lowest were returned. Each score returned was obtained from dividing the total sentiment scores of tweets emitted from the state by the number of those tweets. A greater value reflects a more positive perception and vice versa. This project referred to the words database "AFINN-111" which is distributed under [Open Database License (ODbL) v1.0](http://www.opendatacommons.org/licenses/odbl/1.0/) for the sentiment scores computation and to the coordinates database provided by [polygonzo](https://code.google.com/p/polygonzo/source/browse/shapes/json/us-states.json) for the determination on the location from where a tweet was emitted. To further explore the public's opinions on the topic, the ten most frequently called hashtags were also returned.

>The script was produced using Python 2.7 on an ubuntu 12.04 32-bit linux image. The result, "result.txt", and the script, "sentiment_analysis.py", are availiable in the main repo.

Note: A total of 37861 tweets, not all emitted from the U.S., were collected on August 11, 2014 for this analysis.

Note: Only states from which at least one tweet emitted would appear in the result.

