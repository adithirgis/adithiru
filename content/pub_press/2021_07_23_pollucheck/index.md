---
author: Adithi R. Upadhya, Pratyush Agrawal, Sreekanth Vakacherla, and Meenakshi Kushwaha
categories:
- Research
- R
- Shiny
date: "2021-07-23"
draft: false
excerpt: Journal of Open Source Software
featured: true
layout: single
links:
- icon: file-pdf
  icon_pack: fas
  name: Paper
  url: https://joss.theoj.org/papers/10.21105/joss.03435
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/adithirgis/pollucheck
show_post_time: false
summary: Journal of Open Source Software
subtitle: Journal of Open Source Software
title: pollucheck v1.0, A package to explore open-source air pollution data
---

## Summary 


Air pollution impacts human health, quality of living, climate, and the economy. To assess its impact and facilitate mitigation actions, quantification of air pollution is vital. Measurements are the most accurate way of quantifying air pollution. Many countries conduct regulatory measurements of various air pollutants (e.g., fine and respirable particulate matter, nitrogen dioxide, sulfur dioxide, and surface ozone) and make the data available publicly.

Air pollution data sets typically span several seasons or years and real-time data are recorded typically every hour or at a higher frequency. With the ever increasing amount of data and number of data providers, there is a clear need for tools to handle, analyze, and visualize large data sets. The current Shiny app `pollucheck` aims at a simple workflow to generate a suite of statistical plots and summary statistics.  Users do  not need any programming background to analyze time series data and generate a variety of plots.

`pollucheck` can handle real-time pollution and co-located meteorological data (if available) from the three most popular open-source air pollution databases: [OpenAQ](openaq.org), [AirNow](airnow.gov), and [Indian Central Pollution Control Board (CPCB) dashboard](app.cpcbccr.com). While CPCB data are specific to Indian regulatory monitoring stations, OpenAQ hosts the global open-source pollution databases and AirNow hosts the global PM~2.5~ (mass concentration of particulate matter with an aerodynamic diameter less than or equal to 2.5 microns) data, collected under the United States Embassy and Consulates' air quality monitoring programmes.

The output of `pollucheck` is displayed in seven tabs. Different packages used for building `pollucheck` include `tidyverse`, `openair`, `shiny`, `bslib`, `forecast`, `biwavelet`, `readxl`, `DT`, `data.table`, `nortest`, and `zoo`.