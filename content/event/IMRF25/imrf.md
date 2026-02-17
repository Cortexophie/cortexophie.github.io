---
title: Poster at the 23rd International Multisensory Research Forum (IMRF)
event: IMRF 2025
event_url: https://imrf2025.sciencesconf.org
location: Durham, UK

draft: false
type: event

summary: A presentation of my recent work on computational modelling of human echolocation.

abstract: 'Human echolocation relies on the dynamic integration of auditory feedback and motor behaviour to
localize sound-reflecting targets. Inspired by behavioural paradigms in which blind participants use
echoacoustic clicks to localize objects, we developed a computational model to explore predictive
updating during echo-guided target localisation. Specifically, we implemented a Kalman Filter (KF) as
a control policy that estimates horizontal target azimuth from echo measurements and adaptively
adjusts head orientation in one-dimensional space. Although not a direct model of neural computation,
the KF serves as a dynamic state estimator simulating how noisy external cues can reduce spatial
uncertainty through action. Measurement reliability was modulated by the angle between head
direction and target azimuth, reflecting the directionality of echolocation emissions. This was modelled
as a scaled cardioid function of azimuthal eccentricity, where larger head-target relative angles yield
noisier echo signals., We tested the KF-guided model under two conditions: a test condition with
clicks and a control condition without clicks. Simulated data from multiple participants revealed that
the KF model achieved localization error and convergence rates comparable to real-world human
data, while the control condition failed to converge. Learning dynamics showed consistent
improvement across trials in the KF condition, absent in the control model. Curve fits to trial error
profiles revealed reliable convergence dynamics. These findings suggest that simple predictive
computational approaches can reproduce key aspects of echo-guided sensorimotor learning, offering
a computational foundation for interrogating the mechanisms of echolocation ability in humans, and a
framework for developing more complex biologically grounded models.'

# Talk start and end times.
date: '2025-07-16T15:00:00Z'
date_end: '2025-07-16T16:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: 
  - admin
  - James M. Couglan
  - Santani Teng
tags: 
  - past talks

# Is this a featured talk? (true/false)
featured: false


image:
  caption: 'Poster presented at IMRF 2025'
  focal_point: Smart
  preview_only: false

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
slides: ""

# Projects (optional).
projects: [echolocation]
---
![IMRF poster](imrf25.png)


