---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Text Analysis of 2020 Congressional Election Candidates"
subtitle: ""
summary: "This project involved analyzing the language found on the campaign websites and Twitter feeds of 2020 congressional election candidates."
authors: []
tags: []
categories: []
date: 2020-05-16T10:42:50-04:00
lastmod: 2020-05-16T10:42:50-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
This is a research project that I worked on during my time as a Graduate Research Assistant at the Massive Data Institute.

In this project, we used text data found on the campaign websites and Twitter feeds of 2020 congressional election candidates to develop various measures of political ideology. We then used these measures to test the effect of ideology on electoral performance. We began by using web scraping techniques to collect text data from the campaign websites of over 1,400 candidates, including both incumbent members of Congress and non-incumbent candidates. The website data was complemented by the content of candidates’ publicly available Twitter feeds, obtained through the Twitter API. After collecting the website and Twitter text data, we employed a variety of preprocessing methods to prepare the data for analysis. Next, we utilized techniques like cosine similarity, custom dictionary methods, and a wordfish model to score each candidate on an ideological scale. Finally, we used these ideological scores to assess the relationship between ideology and electoral performance. Preliminary results suggest that being more moderate, as opposed to being more liberal for Democrats or more conservative for Republicans, is associated with stronger electoral performance (as measured by vote share percentage).
