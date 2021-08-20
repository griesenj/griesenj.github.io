---
title: "Disc Golf Data Visualization"
excerpt: "Java driven illustration of Michigan disc golf course growth over time."
layout: single
author_profile: true
header:
  teaser: /assets/images/discGolfVisualizationStatic.png
gallery:
  - url: https://i.redd.it/7hurxqtu6rc61.gif
    image_path: https://i.redd.it/7hurxqtu6rc61.gif
toc: true
toc_label: "Disc Golf Data Visualization"
toc_icon: "cogs"
---

[View project source code on GitHub](https://github.com/griesenj/DiscGolfVisualization)

## Overview

Throughout the years I have played disc golf, the rapid expansion of the sport over time has been incredibly obvious to anyone playing attention. The courses I regularly play are busier in general, and an impressive number of new courses have popped up across the country. I felt that it would be an interesting endeavor to visualize this rapid growth within the state of Michigan. As such, I utilized geolocation data scraped from dgcoursereview.com to plot the addition of new courses over time via the Java GeoTools Library. The result is a color-coded .gif that covers 40+ years of course expansion within the state (with each second of time passage denoting a single year).

## Technologies

* Java
* Selenium Framework
* GeoTools Library
* Eclipse IDE

## Outcomes

This project was a great example of the ability to apply programming concepts directly to a personal area of interest, and I am incredibly happy with the top-down perspective the finished product provides. If there is any single change I would make to the final project, it would be related to the color-coding. I feel that the orange and yellow coloration of the 1990s and 2000s are somewhat difficult to differentiate, and this is certainly something I would address with any future data visualizations.

As an interesting aside, I also posted this visualization to the [disc golf subreddit](https://old.reddit.com/r/discgolf/comments/l288cm/michigan_disc_golf_course_growth_over_time_xpost/?ref=share&ref_source=link) as a contribution to the community and to gather some feedback on my approach. I was very pleased to see that the reception there was incredibly positive (so much so that several community members requested similar visualizations for their home states). I haven't yet tackled these requests, but I feel that they would be a good basis for automating the .gif creation process to an extent. A utility that accomplishes such automation could be an interesting enhancement to make in the future!

## Gallery

{% include gallery %}
