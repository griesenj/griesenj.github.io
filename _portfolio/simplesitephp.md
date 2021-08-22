---
title: "Simple Website"
excerpt: "Simple PHP-oriented website with basic backend data processing. Created for a masters class (CIS501)."
layout: single
author_profile: true
header:
  teaser: https://raw.githubusercontent.com/griesenj/SimpleSitePHP/main/.github/screenshots/page1.png
gallery:
  - url: /assets/images/phpSite1.png
    image_path: assets/images/phpSite1.png
  - url: /assets/images/phpSite2.png
    image_path: assets/images/phpSite2.png
  - url: /assets/images/phpSite3.png
    image_path: assets/images/phpSite3.png
  - url: /assets/images/phpSite4.png
    image_path: assets/images/phpSite4.png
  - url: /assets/images/phpSite5.png
    image_path: assets/images/phpSite5.png
  - url: /assets/images/phpSite6.png
    image_path: assets/images/phpSite6.png
  - url: /assets/images/phpSite7.png
    image_path: assets/images/phpSite7.png
toc: true
toc_label: "Simple Website"
toc_icon: "cogs"
---

[View project source code on GitHub](https://github.com/griesenj/SimpleSitePHP)

## Overview

This project was created as a part of a graduate level computer science class with focus on HTML, PHP, and SQLite. Basic backend functionality through PHP was used for web forms and generation of a dynamic HTML table. Read/write operations acted on a text file rather than a formal database based on server-side limitations associated with SQLite. Additionally, this project restricted all use of JavaScript.

The website use case is outlined below:

* The premise of this project was to serve as a local informational disc golf website.
* Links are included to external resources such as courses, gear retailers, and play instructions.
* Provides functionality to sign up and remove an existing email address from a faux mailing list.
* Displays existing roster data and provides a web form allowing new players to add their information to the roster.

To see the website in action please reference the video and static images in the gallery section below.

## Technologies

* HTML
* PHP
* CSS
* Arch Linux (Bash)

## Outcomes

The end result of this project is a functional website hosted on an Apache web server offered by Grand Valley State University to current students. While the actual site is very simplistic (particularly given the usage of a .txt file for backend data persistence rather than a formalized database such as MySQL or SQLite), it was a good opportunity to become more comfortable with the Linux terminal environment and setting up a website in "bare bones" fashion.

## Gallery

{% include video id="0o15g-1zMAo" provider="youtube" caption="SimpleSitePHP Demo." %}

{% include gallery %}
