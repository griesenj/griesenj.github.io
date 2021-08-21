---
title: "Paced"
excerpt: "Video game speedrun timer developed for mobile with JavaScript and React Native."
layout: single
author_profile: true
header:
  teaser: /assets/images/paced-thumbnail.png
gallery:
  - url: /assets/images/paced1.png
    image_path: assets/images/paced1.png
  - url: /assets/images/paced2.png
    image_path: assets/images/paced2.png
  - url: /assets/images/paced3.png
    image_path: assets/images/paced3.png
  - url: /assets/images/paced4.png
    image_path: assets/images/paced4.png
  - url: /assets/images/paced5.png
    image_path: assets/images/paced5.png
  - url: /assets/images/paced6.png
    image_path: assets/images/paced6.png
  - url: /assets/images/paced7.png
    image_path: assets/images/paced7.png
  - url: /assets/images/paced8.png
    image_path: assets/images/paced8.png
  - url: /assets/images/paced9.png
    image_path: assets/images/paced9.png
  - url: /assets/images/paced10.png
    image_path: assets/images/paced10.png
  - url: /assets/images/paced11.png
    image_path: assets/images/paced11.png
  - url: /assets/images/paced12.png
    image_path: assets/images/paced12.png
  - url: /assets/images/paced13.png
    image_path: assets/images/paced13.png
  - url: /assets/images/paced14.png
    image_path: assets/images/paced14.png
toc: true
toc_label: "Paced"
toc_icon: "cogs"
---

**[View project source code on GitHub](https://github.com/griesenj/Paced)**

## Overview

Paced is a project that stemmed from a graduate-level mobile application development class I took over the summer, ultimately serving as my final project deliverable for the course. The project executes Javascript code via React Native to produce an elegant splits timer dedicated to the concept of "speedrunning" a video game.

When speedrunning a given video game, the goal is generally the completion a game (or a subset thereof) as quickly as possible given a predetermined set of constraints. To track improvement over time it is advantageous for the player to use a tool to monitor the successful completion of various segments. These segments can then be compared to previous bests and provide an ongoing benchmark from which to assess the quality of a given speedrun.

A desktop application known as LiveSplit exists that accomplishes many of these tasks, but I found comparable offerings within the mobile space lacking in terms of features and ease of use. This gap served as the impetus for Paced, which strives to be a elegant mobile splits offering for casual and experienced speedrunners alike.

For a detailed overview of the application's operation feel free to watch the presentation video in the gallery section below! You will also find screenshots of the app in action.

## Technologies

* JavaScript
* React Native
* NodeJS
* Expo Go
* Firebase (Cloud data persistence)
* Windows Subsystem for Linux (WSL2)
* Visual Studio Code

## Outcomes

Considering the fact that this was my first attempt at a fully functional mobile application, I am quite happy with the overall project. The process provided me with some practical exposure to JavaScript and the authoring of mobile applications without the need to dive into native code. I also explored the use of hooks to handle React component state without the incorporation of a corresponding class.

Further optimizations to the application would be necessary for the purposes of a full release, as some of my peers reported slight graphical hiccups related to smaller screen sizes on Android devices. With that said, the current iteration of the project is largely functional and accomplishes the use cases I intially set out to achieve.

## Gallery

{% include video id="5up4RnrGAmk" provider="youtube" caption="CIS 657 (Mobile Application Development) project presentation." %}

{% include gallery %}
