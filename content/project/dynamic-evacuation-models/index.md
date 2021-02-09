---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Dynamic Evacuation Models"
summary: "An emergeny evacuation modeling framework to help evacuees in times of any disaster either natural or man-made."
authors: 
- admin
tags: 
- evacuation
- optimization
- model
- pedestrain
  
- categories: []
date: 2021-02-09T19:07:30+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Follow
  url: https://twitter.com/SMore_eehoward
  icon_pack: fab
  icon: twitter


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

### Overview
Among the most serious natural disasters, earthquakes cause severe damages to infrastructures and building, can kill or injure thousands of humans and animals and, in the luckiest circumstances, just make people homeless destroying communities, habitats, economies and mental equilibrium. 
In order to minimise the loss of lives, an effective evacuation plan to cope with worldwide disasters is required.
In this paper we describe a novel approach to timely formulate an evacuation plan of an area struck by an earthquake. The proposed solution leverages on a two-steps modeling framework: 
1. a method that extracts from enriched GIS %(Geographical Information System) 
data a network description of the area to be evacuated; 
2. a dynamic optimization model that calculates the safest paths citizens should follow to reach pre-identified safe areas. While the network is computed off-line at design time, the optimization model, or one of its reductions, can be embedded in a real-time system that, recomputing it several times, can guide citizen after a natural disaster even in case of high dynamic scenario.