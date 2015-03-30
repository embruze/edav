---
layout: post
title: Taxi Data Project Progress Notes 
description: Projects
tags: assignments project
---

## Estimating GPS accuracy using Taxi Data - Danny, Richie Sankara, Emilie

The goal of this project is to use the 2013 NYC taxi data to predict error in GPS locations, specifically focusing on building bulk density as a predictor. We’ve all had experiences where GPS tells us that we’re on top of the empire state building, or in the middle of the east river, so how accurate is GPS data really? 

## Background
Global Positioning System (GPS) devices compute location by determining the distance between a GPS receiver and several (at least four) satellites. Errors occur when the GPS radio signals encounter different conditions (weather, atmospheric conditions) while travelling from the receiver to the satellite, causing. In urban environments with a proliferation of high-rise buildings, GPS devices are much less likely to be accurate both because the device has access to fewer satellites, and because the signal may reflect off surrounding buildings. 

### Current Issues

One of our first, and most significant issues has been determining how to store and access the data. Luckily we were able to access the dataset fairly easily on google BigQuery thanks to Chris Whong who FOILed it from the Taxi and Limousine commission. Unfortunately we are still struggling with storage and processing questions as this is a pretty big data set. At this point we’re planning to focus on yellow cab data although green-cab borough taxi data has recently been made available as well. The yellow cab data is about 300 GB so we are trying to decide how best to parse this into something manageable. Danny, our GIS expert, has thus far been focusing on the initial spatial processing, including determining the best ways to visualize road beds. Richie, Sankara and Emilie have been concentrating determining the right statistical approach as well as determining what other projects have been done in this area that we might be able to incorporate. 

### Overall Project Plan
1. 	Review existing data and related projects - what could we apply to the current project?
2.	Access taxi data and determine appropriate storage options (300 GB is pretty darn big)
3.	Construct kernel density estimates and plot them in R
4.	Create initial visualizations of new insights gained
5.	Refine models and visualizations 

### Iteration plan - intial sprint

1. 	Review existing data/visualizations and familiarize ourselves with the technical components of GPS data
2.	Get raw data and complete early geoprocessing including roadbed shapefiles
3.	Determine how to store data and work collaboratively

