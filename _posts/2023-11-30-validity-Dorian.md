---
title: "Geographic Threats to Validity within Holler (2021)"
last_modified_at: 2023-11-30T16:20:02-05:00
categories:
  - Blog
tags:
  - GIS
  - Science
  - Uncertainty
  - Discussion
---

For the replication of the [Dorian study](https://github.com/GIS4DEV/OR-Dorian), we will be using X/Twitter data from Hurricane Ida. 
Since the study uses centroids and kernel density for the heat map, the replication should take into account the potential for spurious location and diffusion.
The replication should also emphasize the importance of normalization, as the heat map could just reflect population dynamics.
The different normalization method (having to use Census API instead of X/Twitter data) may make it harder for us to compare certain figures to the original study.
Additionally, the hot spot/cluster figure of the study may be affected by the modifiable areal unit problem, so we should be aware of the state population data we use during the normalization process.

The broad impact of such a replication may be limited as X imposes more restrictions and obstacles to obtaining user data for research. 
After almost a semester of learning about reproducibility and replicability in a geography context, I recognize the role ever-changing technological advances (whether an update or a new restriction) can have on a study’s relevance and validity. 
Additionally, as some governments/emergency-based alert systems [grapple with X’s new platform and business practices](https://www.reuters.com/world/europe/twitter-not-suited-emergency-communications-dutch-say-after-storm-2023-07-05/), the future of X as one of the go-to platforms for live alerts for/reactions to natural disaster events remains uncertain.


**References**

Schmitt, R. R. 1978. Threats to validity involving geographic space. *Socio-Economic Planning Sciences*, 12(4), 191–195. (https://doi.org/10.1016/0038-0121(78)90044-7)[https://doi.org/10.1016/0038-0121(78)90044-7]