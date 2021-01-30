# GEOG 458 - Lab 2
## Corin Zarkowski
___
### Tweets from 7-7:30PM PST regarding Gamestop and the recent stock market phenomenon
![Map](/img/lab2-map.png "Tweets regarding the recent stock market activity.")

- Location: I scraped tweets globally, but since there were only a few tweets regarding the U.S. stock market outside the U.S., I ended up centering the map only on the United States. I decided to scrape tweets globally to glean a larger dataset, as I was having trouble amassing enough tweets about this situation. Even with a 10 minute stream, I still have a small dataset. One major cause of this is that even though I scraped thousands of relevant tweets, only a small fraction of them were geotagged.

- Keywords: ['GMC', 'Gamestop', 'WSB', 'Robinhood', 'Reddit', 'Wall Street', 'Stock']. I initially attempted to use more words to gain a broader dataset, but found that in using words such as 'Short' or 'Market', even though the dataset grew in size, it became bloated with irrelevant tweets. I ended up deciding that a smaller, more accurate dataset would be more beneficial than a larger one with inaccuracies.

- Findings: Tweets are generally skewed towards the north end of the east coast. This may be due to its near proximity to Wall Street, or just population density. I scraped the tweets at around 7pm PST, so I initally expected more tweets from the west coast due to the generally higher activity at 7pm than 10pm. There is also a cluster of activity in Austin, Texas. This may be due to its generally younger demographic--as a phenomenon caused by and most prominent on social media, it would make sense for younger people to be more invested and outspoken. Overall, I did not have enough data points to perform an accurate analysis, but some geographic patterns in the data were still visible.

**NOTE: The output of the final cell in my crawler .ipynb is omitted because its large size was causing a ton of problems with saving and downloading.**
