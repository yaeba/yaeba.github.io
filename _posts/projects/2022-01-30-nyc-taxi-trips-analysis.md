---
title: "New York City Taxi Trips Analysis"
excerpt: "Analysis and modelling on the New York City Taxi Trip data that contains millions of trip records, all in R"
tags: visualization
header:
  teaser: /assets/images/teaser-taxi.jpg
---

If you are a big fan of R, then this is for you.

## Overview

Using [R Markdown](https://rmarkdown.rstudio.com/) and [knitr](https://yihui.name/knitr/), I created 2 open-source notebooks - one for visualization and one for modelling.

Both notebooks were rendered to HTML documents and they contain not only the code to do ETL, plotting and modelling, but the actual report and comments on findings as well.

The reports and findings are completely [reproducible](https://en.wikipedia.org/wiki/Reproducibility#Reproducible_research) - in that the results are accompanied by the data and code needed to produce them.

You can find the code for notebooks at this [repo](https://github.com/yaeba/nyc_taxi_trips_analysis)

## Key libraries used

- [ggplot2](https://ggplot2.tidyverse.org/) - for data visualization
- [tidyverse](https://https://www.tidyverse.org/) and [data.table](https://cran.r-project.org/package=data.table/vignettes/datatable-intro.html)- for manipulating dataframes
- [H2O](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/faq/r.html) - for modelling purposes

## Report 1: Visualization

Read the visualization report [here](https://yaeba.github.io/nyc_taxi_trips_analysis/nyc_taxi_trips_analysis_visualization.html).

> The aim of this study is to gain an initial insight into the open source taxi and weather datasets for the year 2015 in the New York city. In the notebook, I will be dealing with millions of taxi trips data, performing initial exploratory data analysis on taxi usage and visualizing the relationships with other attributes.

> In summary, I performed an initial analysis on the green taxi data that contains millions of trip records entire in R - in a reproducible manner. With ggplot and tmap, I depicted the relationship between attributes and geospatial visualization onto map of New York City taxi zones, and then attempted to answer a few questions for the study, using the figures and plots produced.

## Report 2: Modelling

Read the modelling report [here](https://yaeba.github.io/nyc_taxi_trips_analysis/nyc_taxi_fares_analysis.html)

> The aim of this project is to make a qualitative analysis and gain insights into the open source New York City Taxi and Limousine Service Trip Record Data. In the notebook, I will tackle a research problem and perform analysis on millions of taxi trips data.

> In short, I performed an analysis on taxi fares using the green taxi data that spans from year 2014 to 2015 entirely in R - in a reproducible manner. I reported the taxi fare and its relation with other attributes as an attempt to shed light and infer the hypotheses proposed. Then, statistical models were fitted on training set and evaluated using validation set, each of which contains 3 million records each. Models were then compared, interpreted and a final model was chosen after refining the models. Finally, suggestions for further improving the performance were given.
