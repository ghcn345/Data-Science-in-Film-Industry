![marquee](/images/marquee.jpg)

# Windows-Movie Maker

**Authors**: Ning Chen, Joe Marx

## Overview

Tasked with helping Microsoft Corporation venture into the Film industry, this project analyzes the state of the filmindustry and looks at what kinds of films are most profitable and popular. The needs of a new movie studio is analyzed using exploratory data analysis to generate insights for a business stakeholder. All data is collected by using TMDB API and web scraping from IMDB website.  


## Business Problem

As the tech industry continues to evolve and mature, companies are expanding the scope of services they offer. To stay competitive with peer companies such as Amazon, Apple, and Google, Microsoft can make original video content to offer its massive customer-base. To enter the industry it would be valuable to have a more than superficial snapshot of the industry as it stands. It would be helpful to know what kinds of movies are most popular to produce, what kinds of movies are the most profitable, and what movies receive the highest acclaim from audiences and critics? This will help Microsoft know what their peers believe are the best types of movies to produce and will help them decide what types of movies will make them the most for their shareholders and what will help them be taken seriously in the industry. 


## Data

Robust movie databases, such as the *International Movie Database* (IMDb) and *The Movie Database* provide troves of valuable information on movies released to the public. These two databases were the source for this project's data. 10,000 movies were sampled randomly through *TMDb's* "discover API and was combined with a set of over 40,000 movies produced in the last five years. Movies in this set with missing financial data was supplemented where possible through scraping IMDb's website. This project focuses on return on investment using budget and global revenue data and also explores how well movies are liked and how many movies of different types are produced.


## Methods

After cleansing our data (which proved a guargantuan task), we applied basic descriptive statistics by calculating the mean and median budget, revenue, and profit for various years and various genres. We looked at the average rating on a scale from 1-10 for movies of various categories, we calculated return on investment(ROI) for each film in our data set


## Results

The movie industry is very negatively impacted by COVID-19 in 2020, as evidenced by this year's profits compared to previous years. Comedy, Thiller, and Action movies are dominant in the mainstream movie market. Animation, Fantasy, and Science Fiction movies however, are the most profitable. Most movies are rated around 6-7 out of 10. Documentary, History and War movies are rated above the median.

***

### Visual 1
![graph1](/images/box.png)

## Conclusions

We make the recommendation to Microsoft to consider making Animation, Family, or Horror movies if profit maximization is the goal. There is a trend of higher revenue per dollar spent in these category and so assuming profit maximization as the objective of this venutre, this is the safest choice from a business perspective. If high ratings is the goal, Documentary, Historical, and Musical films would be the strongest choice. Please note, the scope of this project is limited only to the quantifiable data on movie production and doesn't attempt to look at artistic merit of a movie. This statistical analyses also only looked at genre as an input, and didn't include parameters such as artistic and marketing talent attached to movies. It will be challenging to disrupt this industry as a newcomer, especially one with historically high competition, and looking at what genres are most successful among production companies that are already successful may not offer the most useful insights in how to most effectively enter the market. It could prove more valuable to look at what other companies have done to make succssful sojourns into the industry. 


## For More Information

Please review our full analysis in [our Jupyter Notebook](/project-phase1.ipynb) or our [presentation](/presntation.pdf).

For any additional questions, please contact **Joe Marx—jmarx@hash.fyi, Ning Chen—chen.ning345@gmail.com**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project                  <- Narrative documentation of analysis in Jupyter notebook
├── Project_Presentation.pdf            <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code

```
