---
author: Adithi R. Upadhya, Pratyush Agrawal, Sreekanth Vakacherla, and Meenakshi Kushwaha
categories:
- Research
- R
- Shiny
date: "2020-06-20"
draft: false
excerpt: Journal of Open Source Software
featured: true
layout: single
links:
- icon: file-pdf
  icon_pack: fas
  name: Paper
  url: https://joss.theoj.org/papers/10.21105/joss.02250
- icon: github
  icon_pack: fab
  name: Example
  url: https://github.com/meenakshi-kushwaha/mmaqshiny#mmaqshiny-v10-r-shiny-package-to-explore-air-quality-mobile-monitoring-data
show_post_time: false
summary: Journal of Open Source Software
subtitle: Journal of Open Source Software
title: mmaqshiny v1.0, R-Shiny package to explore Air-Quality Mobile-Monitoring data
---

## Summary 


Stationary air quality monitors do not capture spatial variations in air pollution. Mobile-monitoring or "sensors on a mobile platform", is an increasingly popular approach to measure high-resolution pollution data at the street level. Coupled with location data, spatial visualisation of air quality parameters helps detect localized areas of high air pollution, also called hotspots. In this approach, portable sensors are mounted on a vehicle and driven on predetermined routes to collect high frequency data (1 Hz). Analysing this data involves cleaning and combining location data with pollutant data from different instruments. Some instruments are sensitive to factors like signal attenuation, humidity and vibrations; and require additional correction algorithms that are unique to each instrument. A typical mobile-monitoring campaign involves collecting millions of data points and a high burden of quality assurance and quality control. Our package attempts to automate and simplify the process using a Shiny app.

The package `mmaqshiny` analyses, visualises and produces a spatial map of the high-resolution air quality data collected by specific devices installed on a moving platform. With the click of a button, the app generates: summary statistics, time-series plots and spatial maps of pollutant concentrations. The app thus reduces the time consumed in analysing each pollutant individually. It also helps check the quality of the data at near real-time (same day) and instantly visualise pollution hotspots. The time-series plots of each pollutant help in understanding the temporal patterns of concentrations and performance of the instruments. The app can effectively assist air pollution researchers and citizen scientists interested in conducting mobile measurements.


Specific details of instruments and parameters measured can be found in the "Instrument Details" section. `mmaqshiny` package can handle high frequency (1 Hz) measurements collected by popular portable instruments. Specifically, the following parameters are measured: PM~2.5~ (mass concentrations of particulate matter with size less than 2.5 microns), black carbon mass concentrations (BC), ultra-fine particle number concentrations; carbon dioxide (CO~2~), GPS coordinates and relative humidity (RH).
