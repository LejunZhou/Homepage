---
title: On-demand Meal Delivery Routing Problem
summary: Lejun Zhou, Anke Ye, Simon Hu
tags:
  - Transportation
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Meal Delivery
  focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Meal delivery services provided by platforms with integrated delivery networks are becoming increasingly popular. The objective of the project was to design an algorithm that efficiently groups the orders into bundles and then optimizes the delivery routes for couriers accordingly. The meal delivery routing problem (MDRP) is a large-scale NP-complete problem. There is no efficient solution algorithm has been found. Another challenge in the study was the dynamism of order information. The large randomness in user requests makes it hard to predict. We only have limited short-term information at each decision time interval. To solve the MDRP, I proposed a four-stage heuristic algorithm with rolling-horizon implementation. In the first stage, I aimed to combine unassigned orders into bundles for each restaurant based on spatiotemporal information that minimizes the total delivery time, which is equivalent to a set partition problem. A large-scale neighborhood search heuristics was used to solve the problem efficiently. In the second stage, I further combined bundles into bundle pairs so that two bundles in a pair can be served by a courier together. This is equivalent to route set generation in a typical vehicle routing problem (VRP). In the third stage, the pick-up sequence of orders in each bundle (pair) was determined by solving many small-scale travel salesman problems (TSP). In the fourth stage, I formulated a matching problem to decide the optimal assignment between bundles (bundle pairs) and couriers, which was solved by the CPLEX integer solver. In the case study, I compared the proposed model with the existing algorithm proposed by Professor Reyes at the Georgia Institute of Technology. Results showed that our algorithm reduces the average click-to-door time by 3.23% compared to theirs. The resulting paper where I served as the first author has been submitted to the 8th International Conference on Models and Technologies for Intelligent Transportation System. The full version of the paper will be submitted to Transportation Research Part B.
