---
layout: single
title: "Exploring MTA Turnstiles Data"
category: Projects
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
---

## Abstract
The goal of this project was to investigate the trend of the New York City metro ridership and factors that contribute to that trend. I worked with turnstile data from the Metropolitan Transportation Authority (MTA), and looked at how the COVID19 pandemic, rideshare services, weather, time of year and time of week potentially affect the subway traffic.

## Design
The COVID-19 pandemic has been devastating to many sectors of the society – public transportation being of them. In this project, the MTA has asked us to investigate when and where they can reduce the number of trains to reduce their budget. Identifying factors that affect the subway ridership will help the MTA maintain their service in a more cost-effective manner.

## The Data
- The primary dataset is the MTA turnstile data of New York City (2015-2022): http://web.mta.info/developers/turnstile.html

	The following columns were used:
	| NAME | DESCRIPTION |
	| ---- | ----------- |
	| C/A | Control Area (A002) |
	| UNIT | Remote Unit for a station (R051) |
	| SCP | Subunit Channel Position represents an specific address for a device (02-00-00) |
	| STATION | Represents the station name where the device is located |
	| DATE | Represents the date (MM-DD-YY) |
	| TIME | Represents the time (hh:mm:ss) for a scheduled audit event |
	| ENTRIES | The cumulative entry register value for a device |
	| EXIST | The cumulative exit register value for a device |
	
	The number of passengers in a time interval was obtained by substracting the earlier _ENTRIES_ from the later _ENTRIES_.
	
- NYC weather data from the National Oceanic and Atmospheric Administration (NOAA) website (2017-2019): https://www.ncdc.noaa.gov/cdo-web/search

- Rideshare services data will come from the NYC Taxi & Limousine Commission (TLC): https://www1.nyc.gov/site/tlc/about/aggregated-reports.page

## Tools
Data retrieval was be done via SQLite. Data cleaning was be done via Python’s pandas package. Data visualization was done with Python’s matplotlib and seaborn packages.

## Findings
