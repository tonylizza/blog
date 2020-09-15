---
layout: post
title: IBM Data Science Capstone Project
published: true
tags: datascience blog
---

# IBM Data Science Capstone Project

This project was completed for the IBM Data Science Capstone Project. The goal was to predict whether or not a car accident is a serious one based on the circumstances of the accident, for example, whether the driver was speeding or whether pedestrians were involved. Traffic accidents remain one of the largest causes of death and serious injury for Americans. In addition to the significant human cost, motorists and logistics companies alike face costly delays due to the impact of these serious crashes on traffic. Lane closures may be required for long periods of time to deal with the results of the accident, for example, to transport injured and/or clear accident wreckage. The goal is to predict the severity of a crash and in so doing, allow drivers to avoid the area, saving time for both motorists and logistics companies.  

## Data Acquisition and Cleaning  

The data used for the analysis was supplied by the Seattle Department of Transportation (SDOT) and consists of tabular data of 194,673 road collisions and their details from the Seattle, WA area collected between 01-01-2004 and 05-20-2020. The data includes location (lat, long, and address), type of collision, number involved (for persons, pedestrians, cyclists, and vehicles), incident date, whether the driver was inattentive, whether the driver was under the influence, and whether the driver was speeding, road conditions, weather conditions, and time of day. The dependent variable is a Boolean value indicating whether the accident was a serious one. 

I cleaned and formatted the data (e.g, removed duplicates, standardized boolean fields to 0/1, replaced null values with the modal column values where appropriate). I also removed data key fields and duplicated columns that were not relevant to the analysis.  

## Data Analysis  

After the data was cleaned, I began the analysis. There were a number of redundant fields
