# R_Julia_GDelt_Mass_shooting
Using R and Julia to analyse Mass Shooting data scraped from API website

The file contains 
- 1 folder containing data
- 1 project Word file
- 4 .ipynb files
  + (Martin) 1 file using R for web-scraping from GDELT API https://blog.gdeltproject.org/announcing-the-gdelt-context-2-0-api/
  + (Martin) 1 file using Julia for web-scraping from GDELT API https://blog.gdeltproject.org/announcing-the-gdelt-context-2-0-api/
  + (Andy) 1 file using R for web-scraping tables from Wiki
  + (Sakthi and Syaida) 1 file using R for wrangling and visualising data

Below is the summary about the project

1.	Brief description of the project
The purpose of the project is to observe how the mass shootings were represented in the articles in America based on tone and volume intensity through the period of time from 2018 to 2020. There were too reasons for choosing this topic. One is that the mass shootings have been a serious problem in the United States that one of them was ranked as the deadliest shooting event and they have been ocurring approximately every 12.5 days. The other is that for this major problem, how the articles mentioned about mass shootings is also the part that we want to discover, as this would affect the readers in terms of ethics. Hence, we would like to provide the data about the mass shootings infromation (number of people died) and how they were represented in the articles (the tone and the volume intensity). After that, the data would be presented under the two sections as following:
-	The tables includes the date that the event occurred, the average tone values, the volume intensity values, URLs of the top articles, and the names of the articles.
-	The charts visualises the average tone, the volume intensity values and total number of people died and injured through the date, and the tone chart.
The first one would include two main parts of the project – webscraping and wrangling data. The result from this could be provided publicly for people who might be in need for the crime text analysis. The second part would be seen as some examples for what information the final tables could provide.

2.	The scope and some terms
Our project would focus on the mass shootings and articles within USA from 01/01/2018 to 09/10/2020 (3 years). The definitions of some term used in the project were listed as below
-	Average tone: We would focus on the average tone of the articles of the day after the incident
-	Volume intensity: We would focus on the percentage between the number of the mass shooting articles and the total articles of the day after the incident
-	Tone histogram: We would focus on the distribution of tone of mass shooting articles for each year.

3.	What data sources you used
The data were collected based on two main parts
-	Part 1: The data about the articles including date, tone, volume intensity and information of articles (url and names) relating to mass shootings.
-	Part 2: The data about the date and information about that mass shooting s(location, number of people get injured and died, and description)
As to part 1, the data was collected from GDELT project website or Global database of society. This website monitors the broadcast, print, and web news from almost around the world and provides the information about people, locations, organizations, themes, and so on.
As to part 2, the data was collected from wikipedia about the list of the mass shooting from 2018 to 2020. 
From this, we combined together to have a final dataset that mainly represents the time, the location, the number of victims, the tone values, the volume intensity values, the description, the urls and the titles. Additionally, the tone histogram data would be set separately from the main dataset, but it would be seen as one of our final output. Through this, we would know about how the media (mainly newspaper) mentioned about mass shooting through times around America based on tone and the number of articles.

4.	Targets
As to the final model of database, for each key words we used for the term mass shooting, there would be two types of final tables as described below
-	A table including dates of the incident, the number of people get affected (died, injured and both), the location, the description, the average tone value, the volume intensity value, the top links (urls) of the articles, and the name of the articles (could be separate for each year)
-	A table for each year listing the average tone value labels, the number of articles for each label, the top links (urls) of the articles, and the name of the articles.
From those final tables we would visualise them following the years. Based on these charts we could see how the articles talking about mass shootings in America.
As mentioned above, the results from this could be used for criminal text analysis, and we would provide some examples with visualisations.

6. Process of the project

![Picture1](https://user-images.githubusercontent.com/55137629/103433631-87424680-4c59-11eb-868c-d4264f342a7e.png)
