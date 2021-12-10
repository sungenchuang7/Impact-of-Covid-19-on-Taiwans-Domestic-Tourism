# Impact of Covid-19 on Taiwan's Domestic Tourism

This is the final group project of the course Introduction to Programming for Data Science. Using official statistics that showed the numbers of visitors to different tourist attractions in Taiwan each month from 2018-2020, we calculated the popularity growth rate of each tourist spot. 

The popularity growth of a tourist attractions (say, Site A) is defined as follows:
(Number of visitors to Site A during the season of interest in year X - number of visitors to site A during the same season in year X-1) / number of visitors to site A during the same season in year X-1

For examples, the growth rate of site A during summer vacation season in 2020 will be:

(its number of visitors during summer vacation season in 2020 - its number of visitors during summer vacation season in 2019) / its number of visitors during summer vacation season in 2019.

Namely, it's the percentage growth rate compared to the number of visitors during the same time period in the previous year. 

Targeting the top 10 tourist attractions, we crawled reviews from Google Maps and performed sentiment analysis on them. Observing words with positive connotations and high frequency of occurrence used to describe the tourist attractions, we were able to infer why certain tourist attractions were more popular than the others. 

We've built a web application using R Shiny. Since the original project was done in Mandarin Chinese, I've translated most stuff in the application. The only thing that I wasn't able to translate is the result of the sentiment analysis because the crawled reviews were all written in Chinese. 

Here's the link to the original web application: https://trainerblade.shinyapps.io/R_group1_final_project/
Here's the translated version: https://sungenchuang7.shinyapps.io/impact-of-covid19-on-taiwans-domestic-tourism/

The website has very easily self-explantory features. Please enjoy exploring the web application yourself. 
