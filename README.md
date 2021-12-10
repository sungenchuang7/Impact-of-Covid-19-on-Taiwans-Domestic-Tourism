# Impact of Covid-19 on Taiwan's Domestic Tourism

This is a Data Analytics/NLP final project done in the course Introduction to Programming for Data Science. Using official statistics that showed the numbers of visitors to different tourist attractions in Taiwan each month from 2018-2020, we calculated the popularity growth rate of each tourist spot. 

The popularity growth of a tourist attractions (say, Site A) was defined as follows:

(the number of visitors a tourist attraction had in the season of interest in the year of interest - the number of visitors the same tourist attraction had in the same season in the year before the year of interest) / the number of visitors the same tourist attraction in the same season in the year before the year of interest

For examples, the growth rate of Site A in summer vacation season in 2020 will be:

(the number of visitors Site A had in summer vacation season in 2020 - the number of visitors Site A had in summer vacation season in 2019) / the number of visitors Site A had in summer vacation season in 2019.

Suppose these numerical values have some numerical values: 
| term | value |
| --- | ----------- |
| the number of visitors Site A had in summer vacation season in 2020 | 1,200,000 |
| the number of visitors Site A had in summer vacation season in2019 | 1,000,000 |

Then the popularity growth rate of the number of visitors to Site A in summer vacation season from 2019-2020 is: 

(1,20,000 - 1,000,000) / (1,000,000) = 1.2 = 120%

Namely, it's the percentage growth rate based on comparison the number of tourist to that in the season in the previous year. 

Targeting the top 10 tourist attractions with the most significat annual growth rate, we crawled reviews from Google Maps and performed sentiment analysis on them. Observing words with positive connotations and high frequency of occurrence used to describe the tourist attractions, we were able to infer why certain tourist attractions were more popular than the others. 

We've built an interactive web application using R Shiny to feature everything described above. Since the original project was done in Mandarin Chinese, I've translated most stuff in the application. The only thing that I wasn't able to translate is the result of the sentiment analysis because the crawled reviews were all written in Chinese. 

Here's the link to the original web application: https://trainerblade.shinyapps.io/R_group1_final_project/ 

Here's the translated version: https://sungenchuang7.shinyapps.io/impact-of-covid19-on-taiwans-domestic-tourism/

The website has very easily self-explanatory features. Please enjoy exploring the web application yourself. 
