---
layout:     keynote
title:      "Poster accepted"
subtitle:   "Non-myopic Layered Bayesian Optimization for Bathymetric IPP"
#iframe:     "//huangxuan.me/pwa-qcon2016/"
navcolor:   "invert"
date:       2024-07-20
author:     "Alexander W. Kiessling"
tags:
    - Poster
    - Robot
    - AUV
    - Path Planning
---

### Conference

IEEE OES Autonomous Underwater Vehicle (AUV) Symposium 2024, Boston.

### Abstract

While the oceans cover more than 70% of the Earth, the vast majority of the ocean floor remains unmapped. In the path towards a fully-mapped seabed, autonomous underwater vehicles (AUVs) equipped with multibeam echosounders (MBES) are becoming the de-facto tools for collecting bathymetry, thanks to their ability to gather high-resolution data regardless of the water depth. However, the massive scale of the areas to survey highlights the need for more intelligent mission planning approaches beyond the standard lawn-mowing pattern (LMP). Informative path planning (IPP) aims to overcome the limitations of this offline planning by enabling the surveying vehicle to plan trajectories online based on the data collected so far. Thus, the vehicle can optimize the mission time to survey feature-rich areas and steer away from less informative ones. In this work we present an IPP method based on Bayesian Optimization (BO) over an stochastic variational Gaussian Process (SVGP) surrogate model of the bathymetry, trained online with uncertain inputs (UIs) which propagate the AUV localization uncertainty to the SVGP. The trajectory optimization is performed in two steps: first, non-myopic waypoint (WP) candidates are selected through Monte-Carlo tree search (MCTS) which is expanded with multi-objective BO over the SVGP-UI; after, a second BO step is carried out to find a feasible vehicle trajectory to those WPs that maximizes information gathered on the way with the MBES. We assess the performance of our approach in simulation against LMP regarding bathymetry reconstruction error and mission time.


