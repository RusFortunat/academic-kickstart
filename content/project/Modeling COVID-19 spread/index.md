---
title: Modeling COVID-19 spread
summary: The COVID-19 pandemic constitutes a severe global health crisis. Many countries have implemented stringent non-pharmaceutical control measures that involve social distancing and mobility reduction in their populations. Once an epidemic outbreak has been effectively contained through non-pharmaceutical interventions, a safe protocol is required for the subsequent release of social distancing restrictions to prevent a disastrous resurgence of the infection. Here I discuss the individual-based numerical simulations of stochastic susceptible-infectious-recovered model variants on lattices.
# tags:
# - Deep Learning
# date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
  preview_only: true

# links:
# - icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

The COVID-19 pandemic constitutes a severe global health crisis. Many countries have implemented stringent non-pharmaceutical control measures that involve social distancing and mobility reduction in their populations. This has led to remarkably successful deceleration and significant “flattening of the curve” of the infection outbreaks, albeit at tremendous economic and financial costs. At this point, societies are in dire need of designing a secure (partial) exit strategy wherein the inevitable recurrence of the infection among the significant non-immune fraction of the population can be thoroughly monitored with sufficient spatial resolution and reliable statistics, provided that dependable, frequent, and widespread virus testing capabilities are accessible and implemented. Until an effective and safe vaccine is widely available, this would ideally allow the localized implementation of rigorous targeted disease control mechanisms that demonstrably protect people’s health while the paralyzed branches of the economy are slowly rebooted.

Mathematical analysis and numerical simulations of infection spreading in generic epidemic models are crucial for testing the efficacy of proposed mitigation measures, and the timing and pace of their gradual secure removal. Specifically, the employed mathematical models need to be (i) stochastic in nature in order to adequately account for randomly occurring or enforced disease extinction in small isolated communities, as well as for rare catastrophic infection boosts and (ii) spatially resolved such that they properly capture the significant emerging correlations among the susceptible and immune subpopulations. These distinguishing features are notably complementary to the more detailed and comprehensive computer models utilized by researchers at the University of Washington, Imperial College London, the Virginia Bioinformatics Institute, and others.
