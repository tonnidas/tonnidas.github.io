---
title: Health Insurance prediction using supervised learning technique
summary: Predicting health insurance cost for several demographic population.
tags:
- Machine Learning
date: "2021-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
# url_pdf: ""
url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.

# slides: example
---

Since its emergence, health insurance has increased in popularity in both developed and developing countries. Underdeveloped countries are now working toward developing a healthcare system to assist people in avoiding bankruptcy due to medical expenses. Individuals who have health insurance have the advantage of paying a lower amount for medical care than the bill, which helps them deal with unexpectedly high medical bills. Government or private entities offer health care packages. For several organizations, such as hospitals, an accurate estimation of health costs is important. It necessitates the prediction of insurance costs based on an analytical dataset of important individual variables such as age, average monthly medical costs, and so on. In this paper, we investigate the dataset from Brett Lantz's book Machine Learning with R which was simulated using demographic statistics in the United States, and we compare the efficiency of various models in predicting insurance costs on this dataset. To predict the cost, we employed Linear Regression, Ridge Regression, Support Vector Regression, Regression with Neural Network, and Random Forest Regression, and we faced overfitting issues by running several experiments with tuning the hyper-parameters of the best performing model.