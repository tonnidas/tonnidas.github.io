---
title: Registering team in contest
summary: A SpringBoot application for registering, promoting, modifying teams in contests.
tags:
- Software
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

Due to the lack of more variate, native and continuous datasets, sign languages are low-resources languages that can benefit from multilingualism in machine translation. In order to analyze the benefits of approaches like multilingualism, finding the similarity between sign languages can guide better matches and contributions between languages. However, calculating the similarity between sign languages again implies a laborious work to measure how close or distant signs are and their respective contexts. For that reason, we propose to support the similarity measurement between sign languages through a video-segmentation-based machine learning model that will quantify this match among signs of different countries' sign languages. Using a machine learning approach the similarity measurement process can run more smoothly, compared to a more manual approach. We use a pre-trained temporal segmentation model for British Sign Language (BSL). We test it on three datasets, an American Sign Language (ASL) dataset, an Indian Sign Language (ISL), and an Australian Sign Language (AUSLAN) dataset. We hypothesize that the percentage of segmented and recognized signs by this machine learning model can represent the percentage of overlap or similarity between British and the other three sign languages. In our ongoing work, we evaluate three metrics considering Swadesh's and Woodward's list and their synonyms. We found that our intermediate-strict metric coincides with a more classical analysis of the similarity between British and American Sign Language, as well as with the classical low measurement between Indian and British sign languages. On the other hand, our similarity measurement between British and Australian Sign language just holds for part of the Australian Sign Language and not the whole data sample.

#### Why I have done it:
- I developed this project as a research work for Baylor AI lab while working as a research assistant at Baylor University. 

#### When I have done it: 
- While I was in my second semester (Fall 2021) at Baylor University.

#### Technical details: 
- I used Python, tensorflow for this project.
