---
author: Adithi R. Upadhya
categories:
- shiny
- air quality
- R
- package
- open source
date: "2021-08-21"
draft: false
excerpt: This theme has a form-to-email feature built in, thanks to the simple Formspree
  integration. All you need to activate the form is a valid recipient email address
  saved in the form front matter.
layout: single
links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/adithirgis/pollucheck
- icon: newspaper
  icon_pack: far
  name: Paper
  url: https://joss.theoj.org/papers/10.21105/joss.03435
subtitle: 
tags:
- R
title: pollucheck
---

## Abstract

<img src = "featured-hex.png" alt = "Logo of shiny R package pollucheck with Pollucheck and ILK Labs written on it." width = "30%" style = "display: block; margin: auto;" />

*`pollucheck`* can handle real-time pollution and co-located meteorological data (if available) from the three most popular open-source air pollution databases: [OpenAQ](openaq.org), [AirNow](airnow.gov), and [Indian Central Pollution Control Board (CPCB) dashboard](app.cpcbccr.com). While CPCB data are specific to Indian regulatory monitoring stations, OpenAQ hosts the global open-source pollution databases and AirNow hosts the global PM~2.5~ (mass concentration of particulate matter with an aerodynamic diameter less than or equal to 2.5 microns) data, collected under the United States Embassy and Consulates' air quality monitoring programmes.


Pollution data from these sources are typically in different file formats and templates that require customised codes or programmes for analysis. Also, a rigorous quality check of the data is preferred before visualization (plotting) and reporting. *`pollucheck`* offers a single-stop
solution for

(i) handling the pollution data from the open-source databases,

(ii) applying a suite of quality check options,

(iii) generating a variety of summary statistics at various averaging intervals,

(iv) performing time series analysis,

(v) generating a bunch of temporal and statistical plots, and

(vi) comparing data from two input files.


*`pollucheck`* is hosted online on *shinyapps.io* and can be installed to serve locally from [GitHub](https://github.com/).

Load and run `pollucheck` as follows:

``` {.r}
install.packages("devtools")
devtools::install_github("adithirgis/pollucheck")
pollucheck::pollucheck_run()
```
