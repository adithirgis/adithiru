---
author: Adithi R. Upadhya
categories:
- shiny
- air quality
- mobile monitoring
- R
- package
date: "2021-08-19"
draft: false
excerpt: mmaqshiny is a R package which analyses and visualises air quality mobile monitoring data.
featured: true
layout:
links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/meenakshi-kushwaha/mmaqshiny
- icon: newspaper
  icon_pack: far
  name: Paper
  url: https://joss.theoj.org/papers/10.21105/joss.02250
- icon: newspaper
  icon_pack: far
  name: CRAN
  url: https://cran.r-project.org/web/packages/mmaqshiny/index.html
subtitle: ""
tags:
- R
title: mmaqshiny
---


## Abstract

<img src = "featured-hex.png" alt = "Logo of shiny R package mmaqshiny with a car, with ILK and CSTEP written on it." width = "50%" style = "display: block; margin: auto;" />

*`mmaqshiny`* is for analysing, visualising and spatial plotting of high-resolution air quality data collected by specific devices installed on a moving platform. With the click of a button, the app generates: summary statistics, time series plots and spatial map of pollutant concentrations. This app reduces the time consumed for analysing each pollutant individually. It helps check the quality of the data at near real time (same day) and instantly visualise pollution hotspots. The time series plots of each pollutant help in understanding the temporal patterns of concentrations and performance of the instruments.


*`mmaqshiny`* is hosted online on *shinyapps.io* and can be installed to serve locally from [GitHub](https://github.com/).

Load and run `mmaqshiny` as follows:

``` {.r}
install.packages("devtools")
devtools::install_github("meenakshi-kushwaha/mmaqshiny")
mmaqshiny::mmaqshiny_run()
```

