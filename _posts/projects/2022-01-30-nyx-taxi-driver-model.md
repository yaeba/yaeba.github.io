---
title: "New York City Taxi Driver Model"
excerpt: "A predictive taxi driver model to maximize the total earnings - based on the popular public NYC Taxi and Limousine Commission (TLC) trip data"
tags: model
header:
  teaser: /assets/images/teaser-taxi.jpg
---

## Overview

We built a predictive model that will **maximize the total earnings** (fare amount + tips) of a yellow taxi driver in New York City.

The model was evaluated in the context of a turn-based game using the real New York Taxi data to simulate a week as a taxi driver.

In the final leaderboard, we managed to secure the **top place** in our cohort of UniMelb in terms of total earnings. We note that our final model leads with a mean earnings of approximately 200 USD and is consistently awarded with a significantly higher number of trips.

It is also worth mentioning that our model outperformed models using advanced machine learning algorithms (eg [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning) and [Reinforcement Learning](https://en.wikipedia.org/wiki/Reinforcement_learning)) built by other teams. The model we implemented features a basic GLM (Generalized Linear Model) Poisson model and a custom probabilistic model - known as "Route Model" in the report.

## Key points

On a high level, here's what we have done:

1. Data ETL using a combination of shell scripting and R
2. Analysis, data exploration and visualization in R
3. Building the machine learning model in Python with [scikit-learn](https://scikit-learn.org/)
4. Implementing various driver AIs in Python
5. Evaluating the driver AIs with shell script

## Links

- Read the full report: [https://yaeba.github.io/nyc_taxi_driver_model/group7.pdf](https://yaeba.github.io/nyc_taxi_driver_model/group7.pdf){:target="\_blank"}
- Source code: [https://github.com/yaeba/nyc_taxi_driver_model](https://github.com/yaeba/nyc_taxi_driver_model){:target="\_blank"}
