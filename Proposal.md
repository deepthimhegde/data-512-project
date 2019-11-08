# Final Project Proposal

## Motivation
Autonomous driving has created a wave in the society in the last decade. The public has displayed highly polarized feelings for and 
against the idea of bringing self-driving cars to road from the outset. This project is an attempt to understand and analyse the general vibe around self-driving 
as expressed on Twitter around end of May in 2015. This was around the time when news was flying about Google's self-driving test initiative - 
[Google to begin testing purpose-built self-driving cars on public roads](https://www.theguardian.com/technology/2015/may/15/google-testing-purpose-built-self-driving-cars-public-roads).
Also around the same time were articles about accidents being caused by self-driving cars - [Self-driving car accidents revealed in California](https://www.bbc.com/news/technology-32691887)

## Dataset 
The dataset files can be found [here](https://www.figure-eight.com/data-for-everyone/).
The raw data file contains 11 columns, but only 3 of the columns will be useful for this analysis. 

| Column | Description |
|--------|-------------|
| sentiment | sentiment score on a scale of 1 - 5 |
| sentiment:confidence | confidence level between 0 - 1 |
| text | body of the tweet |

#### Sentiment scoring: 
  5: very positive <br />
  4: slightly positive <br />
  3: neutral <br />
  2: slightly negative <br />
  1: very negative <br />

#### How was the data collected?  
Contributors read tweets and classified them as very positive, slightly positive, neutral, slightly negative, or very negative. They were also prompted to mark if the tweet was not relevant to self-driving cars.

#### Ethical considerations
The dataset does not contain personally identifiable data such as names or Twitter handle. The tweet itself is a part of the dataset, but even if one could possibly trace the tweets back to the individual, I assume there should be no issues since the tweets are publicly available for anyone on the web to see. 

## Data Licensing 
The permissions are clearly mentioned at the top of the [dataset page](https://www.figure-eight.com/data-for-everyone/). 

>... free for any and everyone to download.

>Each of the following respective data sets are licensed under a Creative Commons Attribution 4.0 International License. By taking the action of downloading any data set(s), you hereby agree to the associated license terms.  Each data set is provided “as is” and any expressed or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose are disclaimed.

## Unknowns/Limitations
This dataset contains tweets from 2015. To the best of my knowledge, there is no such publicly available dataset for the subsequent 
years which could have led to trend analysis and how opinions have changed over time.  

Since there is no thorough description of the distribution of the dataset, it is unclear whether this is a completely 
random sample representative of the population or harbors some biases. It is also hard to evaluate potential biases 
for the same reason. 
