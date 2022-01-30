---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "The Role of Race and Ethnicity in Mortgage Applications in Washington, D.C."
summary: "A series of static and dynamic visualizations exploring the role of race and ethnicity in mortgage applications in Washington, D.C."
authors: []
tags: []
categories: []
date: 2021-01-06T11:40:21-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
The following is a series of static and dynamic visualizations exploring the role of race and ethnicity in mortgage applications in Washington, D.C. Using HMDA data on mortgage applications from 2017, I investigate disparities in the rates at which consumers in various race/ethnicity groups apply for mortgages, the dollar value of the loans they apply for, and the frequency with which they are denied loans. Additionally, because the dataset includes information on the location of each prospective home purchase, I am able to analyze the role of race and ethnicity in mortgage applications from a spatial standpoint. Specifically, I analyze how the composition of applications by race and ethnicity in any given census tract compares to the current population demographics of that tract. 

In addition to viewing the visualizations below, you can find a short article providing context and interpretations for all of the visualizations on this [GitHub page](https://andygreen-1.github.io/HMDA_Data_Race_Ethnicity/). Additionally, the code, raw data, and Tableau workbooks used to produce the visualizations can all be found in this [GitHub repository](https://github.com/andygreen-1/HMDA_Data_Race_Ethnicity).
***
<br/>

*You can click on any of the three static visualizations below to see a larger version of the image.*


[![race_ethnicity_applications](/img/race_ethnicity_applications.png)](https://andykgreen.com/img/race_ethnicity_applications.png)


[![race_ethnicity_loan_amount](/img/race_ethnicity_loan_amount.png)](https://andykgreen.com/img/race_ethnicity_loan_amount.png)


[![race_ethnicity_denials](/img/race_ethnicity_denials.png)](https://andykgreen.com/img/race_ethnicity_denials.png)

<br/>

<iframe seamless frameborder="0" src="https://public.tableau.com/views/treemap_denial_reasons_16083227565410/Dashboard1?:embed=yes&:display_count=yes&:showVizHome=no" width = '1000' height = '900' scrolling='no' ></iframe>

<br/>

<iframe seamless frameborder="0" src="https://public.tableau.com/views/CensusTractApplicationsbyRaceEthnicity/Dashboard1?:embed=yes&:display_count=yes&:showVizHome=no" width = '1000' height = '900' scrolling='no' ></iframe>

<br/>

<iframe seamless frameborder="0" src="https://public.tableau.com/views/DCMapMortgageApplicationsbyRaceEthnicity/Dashboard1?:embed=yes&:display_count=yes&:showVizHome=no" width = '1000' height = '900' scrolling='no' ></iframe>