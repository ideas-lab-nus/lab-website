---
title: 'New paper: Occupancy data at different spatial resolutions: Building energy performance and model calibration'
author: Adrian Chong
date: '2021-01-22'
slug: []
categories: []
tags:
  - Occupant modeling
  - Building performance simulation
  - EnergyPlus
  - Bayesian calibration
  - Uncertainty analysis
authors: ['admin']
featured: no
image:
  placement: 3
  caption: 'Framework for using real data to evaluate the impact of occupant presence on building energy simulation.'
  preview_only: true
subtitle: ''
summary: ''
url_pdf: 'publication/pdf/chong-2021-occupancy.pdf'
---

{{< figure src="featured.png" width="50%">}}

We have a new paper:

> Adrian Chong, Godfried Augenbroe and Da Yan (2021). 
> Occupancy data at different spatial resolutions: Building energy performance and model calibration.
> Applied Energy.
> <a href="https://doi.org/10.1016/j.apenergy.2021.116492"><i class="ai ai-doi"></i>https://doi.org/10.1016/j.apenergy.2021.116492</a>
> <a href="/publication/pdf/chong-2021-occupancy.pdf"><i class="fas fa-file-pdf"> </i></a>

Occupancy is a significant area of interest within the field of building performance simulation. Through Bayesian calibration, the present study investigates the impact of the availability of different spatial resolution of occupancy data on the gap between predicted and measured energy use in buildings. The study also examines the effect of occupancy data on the quality of the constructed prediction intervals (PIs) using the Coverage Width-based Criterion (CWC) metric. CWC evaluates the PIs based on both their coverage (correctness) and width (informativeness). This investigation takes the form of an actual building case study, with nine months of hourly measured building electricity use, WiFi connection counts as a proxy for occupancy, and actual weather data. In general, the building energy model’s accuracy improves with the occupancy and plug-loads schedule derived from WiFi data. Specifically, the Coefficient of Variation Root Mean Square Error (CV[RMSE]) reduced from 37\% to 24\% with an exponential improvement in the PIs quality compared to the results obtained with ASHRAE 90.1 reference schedules. However, the increase in prediction accuracy shrank to 5\% CV(RMSE) and a comparable CWC upon calibrating the base loads of the reference schedules. Increasing the spatial resolution from building aggregated to floor aggregated occupancy data worsened the CV(RMSE) and CWC, suggesting trade-offs between parameter uncertainty and model bias/inadequacy. These results contribute to our understanding of the interactions between model complexity, simulation objectives, and data informativeness, facilitating future discussions on the right level of abstraction when modeling occupancy

## Highlights

* Metric to evaluate probabilistic predictions against measured building energy use.
* Proposed metric considers both correctness and informativeness of predictions.
* Occupancy data reduced prediction errors from 37\% to 24\%.
* Calibrating ASHRAE base schedule fraction substantially reduced prediction errors.
* Higher spatial resolution of occupancy data might result in poorer predictions.

## Paper

For more information, see [the full paper]({{< ref "publication/chong-2021-occupancy" >}}).


BibTeX citation:

```bibtex
@article{chong2021occupancy,
title = "Occupancy data at different spatial resolutions: Building energy performance and model calibration",
author = "Adrian Chong and Godfried Augenbroe and Da Yan",
journal = "Applied Energy",
volume = "286",
pages = "116492",
year = "2021",
issn = "0306-2619",
doi = "https://doi.org/10.1016/j.apenergy.2021.116492",
url = "http://www.sciencedirect.com/science/article/pii/S0306261921000532"
}
```
