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
*This is a project that I worked on during my time as a Graduate Research Assistant at the Massive Data Institute. While the project is still a work in progress, a brief description of the methodology and preliminary results can be found below.*
***
<br/>

#### Project Overview:

In this project, we use text data found on the campaign websites and Twitter feeds of 2020 congressional election candidates to develop various measures of political ideology. We then use these measures to test the effect of ideology on electoral performance. We begin by using web scraping techniques to collect text data from the campaign websites of over 1,400 candidates, including both incumbent members of Congress and non-incumbent candidates. The website data is complemented by the content of candidates’ publicly available Twitter feeds, obtained through the Twitter API. After collecting the website and Twitter text data, we employ a variety of preprocessing methods to prepare the data for analysis. Next, we utilize techniques like cosine similarity, custom dictionary methods, and a wordfish model to score each candidate on an ideological scale. Finally, we use these ideological scores to assess the relationship between ideology and electoral performance. Preliminary results suggest that being more moderate, as opposed to being more liberal for Democrats or more conservative for Republicans, is associated with stronger electoral performance (as measured by vote share percentage). While the project is still a work in progress, potential contributions include: methodological insights into novel techniques for assessing political ideology, substantive insights into the effect of ideology on electoral performance, and the value of the data assets for future analysis by other researchers.
