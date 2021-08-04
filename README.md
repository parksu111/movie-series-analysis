# Movie Series Analysis

This work was done as part of a final project for the class [STAT471: Modern Data Mining](https://apps.wharton.upenn.edu/syllabi/2019C/STAT571402/) at the University of Pennsylvania. This repository contains the data and code (R markdown) for this project. The R markdown published at RPubs can also be found [here](https://rpubs.com/parksu111/796294).

## Introduction
Production companies often release series of movies rather than a single movie alone. Some of these series involve movies building on the plot of previous releases, such as the Bourne Trilogy, while others follow a particular theme or character, such as the James Bond series. We analyze the quality and commercial success of movie franchises and make recommendations on potential sequels.

Using a dataset of movie series we build models to predict the rating and the revenue of the next movie in a series. We consider multinomial regression, CART, and random forest models, and find that they do better than the baseline, usually when a small number of predictors is used. We then look at two subsets of our data and perform a more detailed analysis. The first is James Bond movies. We find that the Bond actor is an important variable in predicting ratings of future Bond films. We also make predictions on the movie coming out in April 2020. The second dataset is movie series containing reboots of series – where the storyline and usually the cast significantly change. We consider various models which can be used to decide if the next movie should be a sequel or a reboot and make recomendations for a few particular movie series.

Lastly, we conduct textual analysis to see if the plots provided by the movie providers show predictive power. The plots from unique movies are often neutral in a way that the filmmakers use narrative tones. This might indicate that the plots could have different implications from the reviews.
