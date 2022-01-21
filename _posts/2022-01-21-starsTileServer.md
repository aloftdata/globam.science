---
title: `starsTileServer` to visualize large spatial data sets
description: Making large spatial data sets accessible for dynamic visualization is challenging, `starsTileServer` facilitates this
background: /assets/images/2022-01-21-starsTileServer.png
author: Bart Kranstauber
categories: [software]
---


To address the challenge of visualizing large archives of weather radar data and bird specific products interactively new technologies were needed. 
The goal of the R package `starsTileServer` is to provide a simple way to add large data sets to a leaflet or shiny applications.
This is an example I use data from meteorological radar to visualize birds and velocities:

![Radar Visualization](/assets/images/2022-01-21-starsTileServer.png)

Although the need arose from visualizing radar data the application is more general.
Because it is possible to provide custom functions pretty much any data that can be projected can be visualized, for example composites or non square grids. 
More examples are available on the [website](https://bartk.gitlab.io/starsTileServer/). There is is also showen how the applications can be made scalable.
Using this it is possible to generate the images needed for longer animations like this example:

<blockquote class="twitter-tweet" data-conversation="none" data-dnt="true"><p lang="en" dir="ltr">Now also with video <a href="https://t.co/CwzEHtAS5F">pic.twitter.com/CwzEHtAS5F</a></p>&mdash; Bart Kranstauber (@bart_kra) <a href="https://twitter.com/bart_kra/status/1463560977144856582?ref_src=twsrc%5Etfw">November 24, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 



