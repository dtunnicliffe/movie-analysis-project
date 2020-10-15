![image](./images/popcorn.jpg)

# Current Movie Industry Analysis

**Author**: Diane Tunnicliffe

## Overview

I have been tasked with assisting Microsoft in their venture into the movie industry. My goal was to explore what type of films are currently doing the best at the box office and to provide these findings to Microsoft's new movie studio executives. My analysis of the movie industry, achieved by garnering data and utilizing descriptive statistics and visualizations, has shown that a larger budget is correlated with a higher worldwide box office gross. By allocating 75 million to 200 million dollars to produce an animated musical movie released in June or November, or allocating 200 to 400 million dollars to produce a live action super hero movie released in April or May, the data shows that a movie studio will be extremely likely to succeed. I have also given recommendations as to which composers should be hired for an animated musical movie, and which directors should be hired for a super hero movie. Microsoft can use this report to target their production budget, genre, creative type, production method, release-time, and crew members of their upcoming movie endeavors to generate the highest amount of revenue possible.

## Business Problem

I have been informed that Microsoft wants a piece of the multi-billion dollar movie-making industry, but that they are unsure of where to begin. The challenge for their new movie studio is that they are ready to jump into the industry but do not have the necessary knowledge to move forward. To assist them with this goal, I have been looking at the movies that performed highest in worldwide box office amounts for the past ten years. By analyzing the movies that have been most successful recently, I can make recommendations about attributes that Microsoft's movies should have in order to achieve the highest revenue. I have based my analysis on four main factors:

* Movie Type (Genre/Creative Type/Production Method): What types of movie content are currently most successful?
* Release Month: When is the most lucrative time of year to release a movie?
* Production Budget: What budget amount tends to achieve the highest box office gross?
* Additional Attributes: Based on these findings, what else do top-grossing movies have in common?
I chose these questions after considering the business problem and combing through the data I obtained. I have determined that the answers to these questions are integral to the steps that should be taken when considering how to produce the most profitable movie in today's world.

## Data

I utilized three different data sources for my analysis in order to have the most comprehensive view of the industry as it currently is.

* OpusData Movie Data: a free dataset available upon request for academic research, comprised of 1,900 movies with a production year from 2006 to 2018, with a production budget greater than or equal to ten million dollars. This dataset contains values for movie name, production budget, domestic and international gross, genre, production method, runtime, and movie board rating.
* Web-scraped data from The-Numbers.com: The Numbers is described as "the premier provider of movie industry data and research services". This website contains domestic, international, and worldwide box office revenue amounts per movie, and allows filtering and ordering of results based on many different criteria. Some of the criteria provided on this site that I found especially useful were the same criteria listed above: title, production budget, domestic and international gross, genre, and production method, in addition to release date and worldwide gross. For the purposes of this project, I generated and scraped reports for the top 100 movies per year, in terms of revenue, from 2010 to 2020.
* The Movie Database (TMDb) API: The Movie Database is a popular database for movies and TV shows. Their API is a system made freely available for data acquisition. There is a very large amount of data available on TMDb; for the purposes of this project, I used it mainly to fill in missing information from my other two datasets as I moved through my analysis.

## Methods

I imported data from reputable sources, then I removed unnecessary data such as duplicates and irrelevant columns. I filled null values via API calls when appropriate. I utilized descriptive statistics as well as visualizations to illuminate trends in the data and isolate key factors for making a successful movie. This approach was appropriate for analyzing trends in the movie industry and common attributes of high-grossing movies, so that I could make informed recommendations.

## Results

![graph](./images/fig3.png)

The highest-grossing genre was Musical.   


![graph](./images/fig4.png)

Out of the top Musical movies, 4 out of 5 were animated children's fiction movies released in November.  


![graph](./images/fig7.png)

The highest-grossing creative type was super hero.  


![graph](./images/fig8.png)

Out of the top super hero movies, 6 out of 7 were animation/live action and released in April or May.  


![graph](./images/fig10.png)

The highest-grossing production methods were animation/live action and digital animation.  


![graph](./images/fig11.png)

By prioritizing the category of animated movies as a whole, we can include animated musical movies without missing out on important high-grossing attributes.  


![graph](./images/fig14.png)

The best month to release a movie varies greatly depending on the type of movie. For super hero movies, April and May are best. For animated movies, June and November are optimal.  


![graph](./images/fig22.png)

The box office gross tends to increase as the production budget increases. For animated movies, the budget should be between 75 and 200 million dollars.  


![graph](./images/fig23.png)

For super hero movies, the budget should be between 200 and 400 million dollars.  



The results of my complete analysis were as follows:
* The genre with the highest gross for the past ten years was Musical genre.
* The creative type with the highest gross for the past ten years was Super Hero movies.
* The highest-grossing production method was digital animation. 
* The musical and animation factors should be combined to achieve the highest gross. (For instance, box office hits such as Frozen and Frozen II.)
* The release month with the highest gross is dependent on the type of movie being released. For animated movies, the optimal release months are June and November. For super hero movies, the optimal release months are April and May.
* The worldwide gross tends to increase as production budget increases. For animated movies, a high production budget would be one between 75 and 200 million dollars, which has been proven to lead to the highest box office gross. For super hero movies, a high production budget would be one between 200 and 400 million dollars. Movies that had budgets in this range include the very successful Avengers movies, as well as other Marvel movies. 
* Some additional attributes of successful movies are successsful directors for super hero movies and successful composers for animated musical movies. I utilized the TMDb API to generate a list of the highest-grossing people for each of these categories.

<i>Please see full Jupyter notebook for complete analysis, results, and visualizations. These two visualizations below provide only a snapshot of the many factors analyzed as a composite; but there is a full breakdown in my complete analysis. </i>

![graph](./images/fig24.png)

![graph](./images/fig25.png)


I am confident that the results I extrapolated from this analysis would generalize beyond the data that I have, with the exception of this year and next year due to the COVID-19 pandemic. By looking at the data up until this year, the trends and correlations I found were true for the past ten years, so I am confident that they will again be true once the world returns to some semblance of normalcy.

If the recommendations that I made are put to use, I am confident that Microsoft will have a successful break into the movie-making industry. From the data, it is clear that all the attributes I have discussed are correlated with high worldwide box office gross, which is exactly what Microsoft will want for their first movies and beyond.





## Conclusions

In conclusion, I would recommend that Microsoft release one of the following two movies, each with four specific recommendations that have proven to be successful combinations:
### Movie Option #1
* an animated kids fiction movie
* with a production budget of 75 to 200 million dollars
* released in June or November
* containing songs by a high-grossing composer with a track record of successful work in digital animation movies, such as Christophe Beck, Robert Lopez, and Kristen Anderson-Lopez, or Heitor Pereira and Pharrell Williams

### Movie Option #2
* a live action/animation super hero movie
* with a production budget of 200 to 400 million dollars
* released in April or May
* directed by a top-grossing director with a history of proven successful superhero movies, such as Anthony Russo, Joe Russo, or Joss Whedon

While the past ten years of data show that this should be a good recipe for success, one limitation is that we are currently in a global pandemic, which has negatively affected many facets of the global economy. The visualizations above displaying movie gross over time clearly show a significant drop in movie gross for this year (2020). However, since movies take quite a bit of time to produce, the expectation is that the market will be trending in the right direction by the time a future movie would be released.

In the future, this analysis could be improved by adding additional data as it becomes available. It could also be expanded upon by determining how much money there is to be made on a streaming platform movie release while theaters remain at low audience capacity. 

## For More Information

Please review my full analysis in [my Jupyter Notebook](./microsoft_movie_analysis.ipynb) or my [presentation](./movie_analysis_slides.pdf).

For any additional questions, please contact **Diane Tunnicliffe** at diane.j.tunnicliffe@gmail.com.

## Repository Structure


```
├── README.md                        <- The top-level README for reviewers of this project
├── microsoft_movie_analysis.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── movie_analysis_slides.pdf        <- PDF version of project presentation
├── movie_notebook.pdf               <- PDF version of Jupyter notebook
├── data                             <- Both sourced externally and generated from code
└── images                           <- Both sourced externally and generated from code
```
