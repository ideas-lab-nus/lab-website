---
title: 'New paper: eplusr: A framework for integrating building energy simulation and data-driven analytics'
author: Hongyuan Jia
date: '2021-01-19'
slug: []
categories: []
tags:
  - Building Enegy Simulation
  - Academic
  - EnergyPlus
  - R
  - Software Development
authors: ['Hongyuan Jia']
featured: no
image:
  placement: 3
  caption: 'Overview of the eplusr framework'
  preview_only: true
subtitle: ''
summary: ''
url_pdf: 'publication/pdf/jia2020eplusr.pdf'
projects:
  - eplusr
---

{{< figure src="featured.png" width="50%">}}

We have a new paper:

> Hongyuan Jia, Adrian Chong (2020). eplusr: A framework for
> integrating building energy simulation and data-driven analytics.
> Energy and Buildings.
> <a href="https://doi.org/10.13140/RG.2.2.34326.16966/1"><i class="ai ai-doi"></i>:10.13140/RG.2.2.34326.16966/1</a>
> <a href="/publication/pdf/jia2020eplusr.pdf"><i class="fas fa-file-pdf"> </i></a>
> <i class="ai ai-open-access"></i>

This paper presents [eplusr](https://cran.r-project.org/package=eplusr), an
[R](https://www.r-project.org/) package for conducting data-driven analytics
with [EnergyPlus](https://energyplus.net/). With a data-centric design
philosophy, the proposed framework focuses on better and more seamless
integration between BES and data-driven analytics. It provides structured
inputs/outputs format that can be easily piped into data analytics workflows.
It also provides an infrastructure to bring portable and reusable
[computational environment](https://hub.docker.com/r/hongyuanjia/eplusr) for
building energy modeling to facilitate reproducibility research.

## Highlights

* Developed an R package that integrates EnergyPlus with data-driven analytics
* Structured inputs/outputs format that can be easily piped into data
* analytics workflows
* Facilitates reproducible simulations through Docker
* Enables flexible and extensible parametric simulations

## Abstract

The abstract follows.

> Building energy simulation (BES) has been widely adopted for the
> investigation of building environmental and energy performance for different
> design and retrofit alternatives. Data-driven analytics is vital for
> interpreting and analyzing BES results to reveal trends and provide useful
> insights. However, seamless integration between BES and data-driven analytics
> current does not exist. This paper presents eplusr, an R package for conducting
> data-driven analytics with EnergyPlus. The R package is cross-platform and
> distributed using CRAN (The Comprehensive R Archive Network). With
> a data-centric design philosophy, the proposed framework focuses on better and
> more seamless integration between BES and data-driven analytics. It provides
> structured inputs/outputs format that can be easily piped into data analytics
> workflows. The R package also provides an infrastructure to bring portable and
> reusable computational environment for building energy modeling to facilitate
> reproducibility research.

## Paper

For more information please see [the paper]({{< ref "publication/jia-2020-eplusr" >}}) and [the project]({{< ref "project/eplusr">}}).


BibTeX citation:

```bibtex
@article{jia2020eplusr,
  title = {eplusr: A framework for integrating building energy simulation and data-driven analytics},
  author = {Hongyuan Jia Adrian Chong},
  year = {2020},
  journal = {*Accepted in Energy and Buildings*},
  url = {https://CRAN.R-project.org/package=eplusr},
  doi = {10.13140/RG.2.2.34326.16966/1}
}
```
