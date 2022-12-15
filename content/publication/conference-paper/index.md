---
title: 'A Four-Stage Heuristic Algorithm for Solving On-demand Meal Delivery Routing Problem'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Anke Ye
  - Simon Hu

# Author notes (optional)
author_notes:
  - 'First Author'

date: '2022-11-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Submitted to 8th International Conference on Models and Technologies for Intelligent Transportation System
publication_short: Submitted to 8th MTITS

abstract: Meal delivery services provided by platforms with integrated delivery networks are becoming increasingly popular. This paper adopts a rolling horizon approach to solve the meal delivery routing problem (MDRP). To improve delivery efficiency in scenarios with high delivery demand, multiple orders are allowed to be combined into one bundle and up to two bundles from two different restaurants can be delivered on one route. Following this strategy, an optimization-based four-stage heuristic algorithm is developed to generate an optimal routing plan in each optimization period. The algorithm first generates bundles according to orders’ spatial and temporal distribution. Secondly, we find feasible bundle pairs. Then, routes for delivering any single bundle or a bundle pair are optimized, respectively. Finally, the routes are assigned to available vehicles. In computational experiments using instances from open datasets, the system’s performance is evaluated in respect of average click-to-door time and ready-to-pickup time. We demonstrate that this algorithm can effectively process real-time information and assign optimal routes to the vehicles. By comparing the proposed method with an existing algorithm and exact solutions generated for a similar scenario, the results indicate that our method can generate solutions with slightly higher service quality and closer to the exact solutions. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false


# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://doi.org/10.48550/arXiv.2212.03505

url_pdf: ''
url_code: ''
url_dataset: https://github.com/grubhub/mdrplib
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://www.istockphoto.com/photo/high-angle-view-close-up-asian-woman-using-meal-delivery-service-ordering-food-gm1324465031-409795411)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - external-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
