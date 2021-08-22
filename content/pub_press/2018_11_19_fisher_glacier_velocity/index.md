---
author: Adithi R. Upadhya
categories:
- Research
date: "2018-11-19"
draft: false
excerpt: ISPRS TC V Mid-term Symposium "Geospatial Technology - Pixel to People", 20-23 November 2018, Dehradun, India
featured: true
layout: single
links:
- icon: file-pdf
  icon_pack: fas
  name: Paper
  url: /pub_press/2018_11_19_Glacier_work/Paper.pdf
- icon: file-pdf
  icon_pack: fas
  name: Conference link
  url: https://ui.adsabs.harvard.edu/abs/2018ISPAr.425..537J/abstract
show_post_time: false
summary: ISPRS TC V Mid-term Symposium "Geospatial Technology - Pixel to People", 20-23 November 2018, Dehradun, India
subtitle: ISPRS TC V Mid-term Symposium "Geospatial Technology - Pixel to People", 20-23 November 2018, Dehradun, India
title: Changes in Velocity of Fisher Glacier, East Antarctica Using Pixel Tracking Method
---

## Abstract

Glacier movement is a crucial factor for assessing cryospheric climate change. Traditional methods of field surveys for studying glacier movement and velocity are often not possible owing to inaccessibility and harsh terrains. Furthermore, as it is not feasible to physically monitor and survey many glaciers around the globe, these traditional methods are limited in their global coverage. Remote sensing is an ideal tool to study such phenomena on a global scale. Optical remote sensing employs techniques such as feature tracking and pixel tracking, whereas, microwave remote sensing uses intensity tracking, speckle tracking, Interferometric SAR and Differential InSAR (DInSAR). 

This study focuses on estimation of glacier velocity and its seasonal variations using the image-matching technique for optical images for the Fisher glacier, a tributary glacier of the Amery ice shelf in Antarctica. The tool used in this study is the COSI-Corr module embedded in ENVI which provides the velocity in both azimuth and range resolution. The principle of estimating velocity using this tool is pixel tracking wherein similar pixels on two images are tracked where one is the master image and the other is a slave. This technique correlates the master and slave images over a time period and generates three outputs: displacements in the East-West and North-South directions and signal-to-noise ratio (SNR) image. Landsat 8 image pairs were used for cross correlation over a time span of four years spanning 2013-2017. With a resolution of 15 m, the panchromatic band (Band 8) was the ideal choice for pixel tracking as the resolution of other bands is coarser. The initial window size for correlation was 64 while the final window size was 16. The resolution of the displacement images produced is dependent on the value assigned for the step size, which was set to 8. The resultant velocity was derived using the result of the two displacement images. The SNR image was used to remove all the pixels from the velocity output having the value of SNR less than 0.9, in order to reduce the effect of noise. 

The annual velocity of the Fisher glacier was estimated to be around 600 to 650 m/yr near the tongue where it merges with the Amery Ice Shelf, which was reduced to 150 m/yr as it recedes. The resultant velocity images have a resolution of 120 m. The seasonal variation in velocity for the year 2013-2014 is 1.8 m/yr, while in the succeeding year 2014-2015 it subdued to 1.7 m/yr. The seasonal variation for the year 2015-2016 was estimated to be 7.9 m/yr. The seasonal variation for 2016-2017 was 17.4 m/yr.
