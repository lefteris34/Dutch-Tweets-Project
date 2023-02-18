Introduction

This project involves analyzing a dataset of Dutch social media tweets from 1-2020 to 9-2020. The goal of this project is to gain insights into the patterns of tweet sentiment and user behavior in the Dutch social media landscape.

Methodology

The project started with importing necessary libraries and reading the dataset. The dataset was explored by checking the head of the data and using various methods to understand the data structure, such as info() and shape.
After that, null values were checked and it was found that the hisco column had a lot of null values. Therefore, the decision was made not to explore this column any further.

Next, the dates were analyzed and it was found that the tweets were from 1-2020 to 9-2020. Some values with the wrong year were also removed from the dataset.

The project then moved onto visualizing the data. Distribution of tweets per month, distribution of tweet sentiment, as well as average sentiment per month were plotted. Another noteworthy observation is that despite the rising COVID-19 cases and deaths during the period of the dataset(total deaths.jpg), sentiment in the tweets showed an overall increase. This could suggest that Dutch people are generally optimistic, or that they have developed a resilience to the ongoing pandemic.
The top 10 users with the most tweets were also analyzed and their sentiment was compared to the mean of all the tweets. Interestingly, it was found that all top 10 users had lower sentiment than the average.

Finally, the sentiment of tweets was analyzed based on the day of the week. It was found that Saturday and Sunday had the least sentiment tweets. It is interesting to see that even though weekends are typically associated with a more relaxed and happy mood, the sentiment of tweets during weekends was actually lower than during weekdays. This could suggest that people use social media to express negative emotions or dissatisfaction more frequently on weekends.

Conclusion

In summary, this analysis of the Dutch social media collection about tweets reveals interesting insights into the sentiment of Twitter users in the Netherlands during the COVID-19 pandemic. Despite rising cases and deaths, the sentiment of tweets appears to have risen over time, indicating a potential sense of optimism among the Dutch population. It is also worth noting that the sentiment of tweets is lowest on weekends, which is contrary to the assumption that people are happier on weekends. These findings could be valuable to researchers studying the effects of the pandemic on mental health and wellbeing, as well as to businesses seeking to understand consumer sentiment in the Dutch market.
