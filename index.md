---
title       : Production Plan Optimisation
subtitle    : Linear Optimisation
author      : HOM
job         : Learner
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Intro & Description
The above app is about linear optimisation (like what solver does in MS Excel).

It is about a fictional company that makes 2 products: Razor and Navajo. It is assumed that the company is so profitable that it can sell all its products.

The production process of each product includes 3 main steps:
- Manufacturing Frame.
- Wheels & Deck Assembly. 
- QA & Packaging.  

The capacity (in hours) at each production step is assumed to be: 5610, 2200, 1200 respectively. So the main goal are to determine How many units of each model should be produced in order to maximise profit. Hence the app will compute the number of units of each model and the maximum profits available. Therefore, the user just needs to input the values and the app will compute the above objective.

Note: that no negative values should be entered.

--- .class #2

## Shiny App: Production Plan Optimisation
![width](assets/img/AppScreenshot.PNG)

--- .class #3

## Linear Constraints

In order to run the application, there are some linear constrainst built in that need to be taken into consideration. The constrains can be summarised in the picture below.

![width](assets/img/Constraints.PNG)

In the picture above, R and N represent the two product models, i.e. Razor and Navajo respectively.

--- .class #4

## Where the idea came from

For full disclosure please note that the linear model used to build this App is a model I picked up from another
Coursera Course (Operations Analytics). However, the Operations Analytics course is entirely taught in Excel and
doesn't involve any R coding. Therefore, all the interfaces in the Shiny App, Slidify and all the R codes are my
own work.

Link to the Operations Analytics Course: https://www.coursera.org/learn/wharton-operations-analytics/home/week/2


