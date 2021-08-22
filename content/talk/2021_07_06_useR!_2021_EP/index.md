---
author: Adithi R. Upadhya, Pratyush Agrawal, Sreekanth Vakacherla, and Meenakshi Kushwaha
categories:
- R
date: 2021-07-06T13:00:00
draft: false
event: useR! 2021, The R Conference
event_url: https://user2021.r-project.org/
featured: true
layout: single
abstract: ""
projects:
  - pollucheck
  - mmaqshiny
links:
- icon: calendar-check
  icon_pack: fas
  name: schedule
  url: https://teamup.com/event/show/id/imF6ZvPzhjPvdixuCjCUME43s4mwaf
- icon: images
  icon_pack: fas
  name: slides
  url: https://user2021-aru.netlify.app/#1
- icon: youtube
  icon_pack: fab
  name: video
  url: https://www.youtube.com/watch?v=Q78nELnN7Sc&list=PL4IzsxWztPdnviiir8c5GaarXd9vZ2TIP&index=23
- icon: github
  icon_pack: fab
  name: Repository
  url: https://github.com/adithirgis/useR_2021
location: Global
show_post_time: false
subtitle: useR! 2021 Elevator Pitch
date_end: 2021-07-06T14:30:00
subtitle: "R packages for air quality data"
summary: "R packages for air quality data"
all_day: yes
publishDate: '2021-08-22'
title: R in the aiR!
---


## Abstract

R is a powerful tool in analysing air quality data. With the ever-increasing global measurements of air pollutants (through stationary, mobile, low-cost, and satellite monitoring), the amount of data being collected is huge and necessitates the use of management platforms. In an effort to address this issue, we developed two `shiny` applications to analyse and visualise air-pollution data.

`mmaqshiny`, is aimed at handling, calibrating, integrating, and visualising spatially and temporally acquired air pollution data from mobile monitoring campaigns. Currently, the application caters to data collected using specific instruments. With just the click of a button, even non programmers can generate summary statistics, time series, and spatial maps. The application is capable of handling high-resolution data from multiple instruments and formats. Moreover, it also allows users to visualize data at near-real time and helps in keeping a tab on data quality and instrument health.

Our second `shiny` application- `pollucheck`, and allows users to handle open-source air quality datasets available from [OpenAQ](https://openaq.org/#/countries/IN?_k=5ecycz), [CPCB](https://app.cpcbccr.com/ccr/#/caaqm-dashboard-all/caaqm-landing), and [AirNow](https://www.airnow.gov/international/us-embassies-and-consulates/#India). Users can visualize data, perform basic statistical operations, and generate a variety of publication ready plots. It also provides outlier detection and replacement of fill/negative values. We have also incorporated the popular `openair` package features in this application.

<div class="shareagain" style="min-width:300px;margin:1em auto;">
<iframe src="https://user2021-aru.netlify.app/#1" width="700" height="500" style="border:2px solid currentColor;" loading="lazy" allowfullscreen></iframe>
<script>fitvids('.shareagain', {players: 'iframe'});</script>
</div>