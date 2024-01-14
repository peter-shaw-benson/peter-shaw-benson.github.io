---
title: "Falling Fruit Seasonality Prediction"
excerpt: "How can we predict plant ripeness based on climate data? <br/><img src='/images/portfolio/example_forecast.png'>"
collection: portfolio
---
*Example forecast visualization is from Taylor & White, 2019.*

During Summer 2023, I was the Engineering Manager for a small team of volunteers with the organization
Develop For Good, a non-profit that provides software engineering services to other non-profits.
My team worked with a non-profit called ["Falling Fruit"](https://fallingfruit.org), whose mission is to provide information about edible plant locations for use in urban foraging.
I was tasked with scheduling and running meetings across multiple time zones, assigning team responsibilities, and assisting with parts of the software writing process.

Our task was to adapt an algorithm described in Taylor & White, 2019, “Automated data-intensive forecasting of plant phenology throughout the United States.” for use with international phenology observations and climate data.
Our team drew data from multiple sources, including ERA-5, ECA&D, NPN, and the phenology observations native to Falling Fruit.
![era-5 map](images/portfolio/era_5.png)

We trained a model that was able to predict fruit ripeness to within one month of the observed ripenesses for 85% of the observation sites in the Falling Fruit database – an impressive achievement given the complexities of data collection, variability of seasons, and site-level geographic variables.
Outside of the leadership aspects, my biggest contributions to the project were formatting data and adapting the software package used in Taylor & White, 2019 for our usage.
