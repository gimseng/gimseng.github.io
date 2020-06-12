# Data science portfolio by Gim Seng Ng

This is a collection of data science project notebooks I created to learn and explore machine learning algorithms.

## End-to-end projects

### Gameplay Data Analysis

Oftentimes, an end-to-end project is both a fun and challenging experience. I decided to pick something that I have enjoyed with questions I sometimes wondered. I enjoy playing video games in my free time and I often use the website [howlongtobeat.com ](howlongtobeat.com) to track my backlogs, I decided to build a data science project using gameplay data.

The motivation comes from trying to understand gamer's playing behavior. Since most (if not all) such data are probably proprietary and private, it is fortunate to have websites that allow users to log playtime and provide ratings. There are probably other websites (such as [Steam](https://steamcommunity.com) and others) which provide better or more data, however, since I am already familiar with howlongtobeat.com (HLTB), with their data being publicly available for web scraping (see their robots.txt), it is both a somewhat challenging but feasible task to do.

What is the end goal? I hope to provide some gross analysis relating to game play behavior, rating and perhaps sales. Sale numbers are not on HLTB, but hopefully (maybe at another project or an extension of this one) I have time to scrap another website for such data and link it to my database from HLTB. With that, there are a few interesting insight questions:

1. Do longer time provide more fun experience? Is this dependent on gender? 
My initial idea is for some games (like action adventure), as long as the quality (for e.g. a good story) is high, a shorter gameplay might be sufficient as long as it is an overall quality experience. For genres which focus on good gameplay mechanics, perhaps a longer playtime will be fun too. Games like Rocketleague, Minecraft or FIFA are simply fun the more you play ! Uncovering this type of intuitions in the data through rigorous analysis will be enlightening.

2. We sometimes see developer 'pad' gameplay with somewhat unimpressive contents. Is this something that we can make quantitative in our data? If not, where else can we supplement our data to be able to explore such questions. The impact will then help developers to avoid doing so, since it might affect future sales.

3. How about gameplay fatigue? For each genre of video game, how long do people typically play before they quit or dislike the games? How to propose a quantitative measure and quantitatively answer this question is something which will be useful for game design as well.

4. Lastly, is there a meaningful way to cluster players based on playtime and perhaps rating? Could this provide a predictive machine learning model? Such a model could then be used for developers when they want to compare a certain playtime profile with another to decide how to proceed with their game development. If we want, we could provide a supervised machine learning model where the predictor / label is the rating of a game, while playtime profile and cluster label can be used as features to predict user rating.

All of the above, and hopefull more, will be explored and answered in the link to the github codes: [Github (https://github.com/gimseng/game_stats)



<!---
[Github](https://github.com/.../.ipynb) 
[nbviewer](http://nbviewer.jupyter.org/github/ ....ipynb)

## Classification problems

## Regression problems

## Natural language processing


## Clustering

## Neural networks

## Data exploration and analysis

## Recommendation systems
--->


