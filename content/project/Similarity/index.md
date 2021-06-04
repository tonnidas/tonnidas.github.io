---
title: Who should be in the hall of Fame
summary: Determining similarity between two objects of the same type.
tags:
- Bigdata
date: "2021-02-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg` to your project's folder and keep this below section for caption. However, caption is optional. 
image:
  caption: Prototype of the Color Sorter
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.

# slides: example
---

A common activity for big data is determining similarity between two objects of the same type. Baseball reference has a formula for computing the similarity of players, found [here](https://www.baseball-reference.com/about/similarity.shtml).

The aim of this project was to look for players that should be in the Hall of Fame, but they are not using [Lahman’s Baseball Database](http://www.seanlahman.com/baseball-archive/statistics/). We say a player should be in the Hall of Fame is at least 3 of the 5 most similar players are in the Hall of Fame. This is also using similarity as the distance function with the kNN problem.

#### Why I have done it:
- I built this project as an assignment for Cloud Computing course while studying at Baylor University. I enjoyed solving these problems with new technologies.

#### When I have done it: 
- While I was in my first semester (Spring 2021) at Baylor University.

#### Technical details: 
- I used pySpark (RDD, Python), Dask (Python, Dask Bag), MongoDB (file system, MongoDB Query Language (MQL)) separately to solve the problem using the public Lahman's Baseball dataset.
