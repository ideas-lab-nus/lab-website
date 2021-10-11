---
date: "2020-08-08T00:00:00+08:00"
external_link: ""
image:
  caption: epwshiftr package
  focal_point: Smart
summary: An R package for creating future weather files under climate changes for building energy simulation
tags:
- Building Performance Simulation
- Climate Change
- Software Development
- EnergyPlus
- R
title: "Epwshiftr: an R package for creating future weather files under climate changes for building energy simulation"
url_code: "https://github.com/ideas-lab-nus/epwshiftr"
url_pdf: ""
url_slides: ""
url_video: ""
---

A free, open-source R package called 'epwshiftr' for adapting EnergyPlus
Weather (EPW) files to incorporate climate change predictions using the
morphing method. The focus of this package is to automatically process big
amounts of climate change model data from the latest CMIP6 GCMs and create
future EPW files for world-wide locations in a user-friendly and flexible way.
It is capable of processing multiple GCM outputs at various spatial and
temporal resolutions. The package is designed into a modularity style. Each
module stores data in a standard data format, which allows to explore
a considerably broad pool of ready-to-use methods available in R for customized
statistical analysis. Most computational-intensive processes have been designed
to run in parallel for speed-up.

### Acknowledgement

This research is supported by the National Research Foundation, Prime Minister’s
Office, Singapore under its Campus for Research Excellence and Technological
Enterprise (CREATE) programme. It was funded through a grant to the Berkeley
Education Alliance for Research in Singapore (BEARS) for the Singapore-Berkeley
Building Efficiency and Sustainability in the Tropics (SinBerBEST) Program.
BEARS has been established by the University of California, Berkeley as a center
for intellectual excellence in research and education in Singapore.
