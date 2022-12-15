---
title: Liquid Medical Oxygen (LMO) Logistics Network Optimization
summary: Lejun Zhou, Lavanya Marla, Varun Gupta, Ankur Mani
tags: 
  - Logistics
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Logistics Network of LMO
  focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Oxygen is an essential life-saving medicine used in several indications at all levels of healthcare. During the COVID-19 pandemic, the demand for liquid medical oxygen (LMO) has increased significantly due to the occurrence of lung infections in many patients. However, many countries and regions are not prepared for the emergence of this phenomenon, and the limited supply of LMO has resulted in unsatisfied usage needs in many regions. In this project, we aimed to design the optimal LMO allocation strategies with trucks and containers. I formulated a linear programming model with the objective to minimize the unsatisfied demand given the constraints of supply and transportation capacity. The decision variables are how much LMO should be transferred from a place to another at each time interval using a specific number of vehicles. Multiple storage points are added into the network to allow for more flexible allocation strategies. Though the model is linear, the dimensionality is large due to a huge number of vehicles and locations, which brings computational challenges in solving. To tackle this problem, I proposed a dimensionality reduction method to simplify the formulation. Binary parameter matrixes were precalculated to indicate whether a vehicle with diversity work is able to return at a time interval or not. With the help of precomputation, the departure and return trips of a vehicle can be modeled as whole (instead of separately in the original formulation), which greatly reduces the problem scale by eliminating the number of decision variables by 90%. The proposed model is implemented in India with real-world LMO supply and demand data as a case study. Numerical results show that the solving time decreased from 3 minutes to 25 seconds with the proposed dimensionality reduction method. Compared to the manually designed allocation strategy, the proposed model reduces the unsatisfied demand by 20%. The project is still ongoing. I keep meeting with Professor Marla and two other professors involved in the project for weekly discussion. We believe there will be academic output soon.
