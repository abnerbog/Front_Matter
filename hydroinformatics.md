---
title: Hydroinformatics
subtitle: A free, open source guide to common hydrology data analyses
date: 2025-01-16
github: https://github.com/VT-Hydroinformatics/Front_Matter
edit_url: https://github.com/VT-Hydroinformatics/Front_Matter/edit/main/foreward.md
author:
  - name: JP Gannon
    orcid: 0000-0002-4595-3214
    url: https://jpgannon.github.io/
    affiliation: 
      - name: Virginia Tech
        url: https://www.vt.edu/
---

# Introduction

_**To help me keep get an idea of who is using this resource so I can improve it in the future, please consider filling out any or all of this survey: https://forms.gle/6Zcntzvr1wZZUh6S7. Thanks!**_

This textbook contains the notes and most exercises for a course on data analysis techniques in hydrology using the programming language R. The material will be updated each time the course is taught. If new topics are added, the topics they replace will be left, in case they are useful to others.

I hope these materials can be a resource to those teaching themselves R for hydrologic analysis and/or for instructors who may want to use a lesson or two or the entire course. Each chapter in this bookdown is linked to a github repository where the code can be downloaded or copied to another github account.

If you have questions, suggestions, or would like activity answer keys, etc. please email me at jpgannon@vt.edu.

The following resources, among others, were very helpful when compiling the chapters of this book. They are also linked in specific chapters, along with other resources. These are great resources if you want to dig deeper into topics covered in this textbook:
- R for Data Science: https://r4ds.had.co.nz/
- Statistical Methods in Water Resources: https://pubs.er.usgs.gov/publication/tm4A3
- Geocomputation with R: https://geocompr.robinlovelace.net/

# How to use these materials

At the top of each chapter there is a link to a github repository. In each repository is the code that produces each chapter and a version where the code chunks within it are blank. These repositories are all template repositories, so you can easily copy them to your own github space by clicking *Use This Template* on the repo page.

In my class, I work through the each document, live coding with students following along. Typically I ask students to watch as I code and explain the chunk and then replicate it on their computer. Depending on the lesson, I will ask students to try some of the chunks before I show them the code as an in-class activity. Some chunks are explicitly designed for this purpose and are typically labeled a "challenge".

Chapters called ACTIVITY are either homework or class-period-long in-class activities. The code chunks in these are therefore blank. If you would like a key for any of these, please just send me an email.

# Table of contents

1. **Intro to Plotting:** *Introduction to plotting with ggplot.*
2. **R Tidyverse Programming Basics:** *Introduction to basic R syntax and dplyr verbs.*
3. **ACTIVITY Intro Skills:** *Activity to practice basic plotting and programming.*
4. **Introduction to Basic Statistics:** *Introduction to basic ways to measure a data distribution.*
5. **ACTIVITY Intro Stats:** *Activity to practice basic statistics concepts.*
6. **Joins, Pivots, and USGS dataRetrieval:** *Joins and Pivots, using USGS dataRetrieval to generate examples.*
7. **ACTIVITY Joins Pivots dataRetrieval:** *Activity to practice Joins, Pivots, and dataRetrieval.*
8. **ACTIVITY Summative 1:** *First summative assessment/practice.*
9. **Flow Duration Curves:** *Building and exploring flow duration curves.*
10. **Low Flow Analysis:** *How to calculate low-flow statistics (ex: 7Q10, 1Q10).*
11. **Flood Frequency Analysis and Creating Functions:** *Flood frequency analysis and making your own functions.*
12. **Geospatial data in R - Vector:** *Intro to working with vector data in R*
13. **Geospatial R Raster - Hydro Analyses:** *Intro to working with raster data in R, hydrological raster analyses*
14. **Summative Assessment 2:** *Summative Assessment #2*
15. **Geospatial R Raster - Watershed Delineation:** *Watershed delineation and extracting DEM values by watershed*
16. **Intro to Modeling - Getting Started with HBV:** *Setting up a simple hydrologic model in R*
17. **Intro to Modeling - Calibrate HBV:** *Using the Monte Carlo method to calibrate the HBV model, discuss equifinality*