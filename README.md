# AutoMobile.tn Web Scraping and Data Visualization

This repository contains the code and data related to web scraping, data cleaning, and data visualization of  the AutoMobile.tn website. The project aims to gather, process, and visualize data on the used cars market and giving it a geospatial aspect  .

## Table of Contents

- [Introduction](#introduction)
- [Web Scraping](#web-scraping)
- [Data Cleaning](#data-cleaning)
- [Data Visualization](#data-visualization)

## Introduction

Briefly introduce your project, its purpose, and the context in which it was developed.

## Web Scraping

The web scraping phase of this project was implemented using Python and the Beautiful Soup library. This process involved extracting data from the AutoMobile.tn website to collect information related to cars Brand, Type , Manufacture_year, Mileage , Price , Body_type , Fuel ,   Horse_Power , Gear_box , Transmission , Color , Governorate , Address .

**Key Steps:**

- Used the requests library to send HTTP requests to the AutoMobile.tn website.
- Iterated through multiple web pages to gather a list of individual announcement then i iterated through these announcement  .
- Employed Beautiful Soup to parse the HTML content of the web pages and extract specific data elements, such as  Brand, Type , Manufacture_year, Mileage , Price , Body_type , Fuel ,   Horse_Power , Gear_box , Transmission , Color , Governorate , Address .

**Challenges:**

- The website structure was hard to deal with and to parse through .

## Data Cleaning

- Cleaning the data was about eleminating doubles, changing columns data types and preparing the data for visualization for that i used Pandas and Geopandas  .

## Data Visualization

- The data Visualization part i used Matplotlib Library to create histogram bars and to show case geospatial files.

![Images](https://github.com/SayehOmar/AutoMobileTN_case_study/blob/main/Images/Average%20car%20price%20by%20brand.png)

- Geospatial Aspect.

![Images](https://github.com/SayehOmar/AutoMobileTN_case_study/blob/main/Images/City%20occurrences%20based%20on%20Cars%20announcements.png)
