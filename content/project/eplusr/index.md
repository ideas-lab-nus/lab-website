---
date: "2020-08-08T00:00:00+08:00"
external_link: ""
image:
  caption: Overview of eplusr framework
  focal_point: Smart
slides: example-slides
summary: A framework for seamless integration between Building Energy Simulation (BES) and data-driven analytics.
tags:
- Building Performance Simulation
- Software Development
- EnergyPlus
- R
title: "eplusr: A framework for integrating building energy simulation and data-driven analytics"
url_code: "https://github.com/hongyuanjia/eplusr"
url_pdf: "publication/pdf/jia2020eplusr.pdf"
url_slides: "https://hongyuanjia.github.io/eplusrIntro"
url_video: ""
---

Building energy simulation (BES) offers an alternative approach that encourages
customized, integrated design solutions, and the development of BES tools has
been pronounced over the decades. The core tools are the whole-building
energy simulation programs that provide users with key building performance
indicators such as energy use and demand, temperature, humidity, and costs.
However, BES, with an iterative nature inside, can produce a large amount of
data. The volumes of the data have overwhelmed traditional data analysis
methods such as spreadsheets and ad-hoc queries with a large number of factors
to be considered. Solutions in most existing software and applications have
limited post-processing capacities on BES results. They are not flexible enough
to enable a clear understanding and control of how the data is being
transformed. There is a need to improve the efficacy and integration between
data-driven analytics and BES, and efforts should be made to develop integrated
tools that are capable of leveraging both methods.

As BES becomes more integral to many aspects of architecture design and
decision-making processes, computational reproducibility has become
increasingly important to researchers, designers and practitioners. Lack of
credibility in BES results due to a lack of reproducibility is widely
considered a problem by the energy modeling community. Issues in simulation
reproducibility are mainly caused by the absence of (1) an integrated workflow
between BES and data-driven analytics and (2) a portable and reusable
computational environment encapsulating essential software and applications to
perform it.

To address these issues, this paper introduces a new framework for integrating
BES and data-driven analytics. The framework is different from existing ones
because of its data-centric design philosophy. The objectives are:

1. to provide better and more seamless integration between BES engine EnergyPlus
   and R-programming data-driven analytics environment through a parametric
   simulation prototype with structured inputs and outputs format.
2. to build infrastructures for portable and reusable BES computational
   environment to facilitate reproducibility research in building energy
   domain.

To achieve seamless integration between BES and data-driven analytics, we
propose a framework consisting of the following:

1. I/O processors for structuring BES inputs and outputs for seamless
   integration with data analytics workflow.
2. A parametric prototype for conducting flexible and extensible parametric
   simulations.
3. A computational environment that is based on Docker containerization
   to facilitate reproducibility research in the energy
   simulation domain.

{{< figure src="featured.png" width="50%">}}

The first two components have been packaged into a free, open-source R package
[eplusr](https://github.com/hongyuanjia/eplusr) which is
distributed using [CRAN](https://cran.r-project.org/package=eplusr) (The
Comprehensive R Archive Network). The third component has been encapsulated
using Docker containerization and is distributed using [Docker
Hub](https://hub.docker.com/r/hongyuanjia/eplusr).

## Get Started with *eplusr*

The source code is hosted on [GitHub](https://github.com/hongyuanjia/eplusr).
The R package can be easily installed using:

```r
install.packages("eplusr")
```

Below shows some feature highlights of the eplusr package:

{{< figure src="view_geometry.gif" caption="View IDF geometry in 3D" width="50%">}}

{{< figure src="autocomplete.gif" caption="Turn RStudio into a model editor via autocompletion" width="50%">}}

{{< figure src="epw.gif" caption="Query and modify weather file" width="50%">}}

{{< figure src="job.gif" caption="Query output via SQL in Tidy format which is much better for data analysis" width="50%">}}

{{< figure src="param.gif" caption="Flexible and extensible parametric simulation interface" width="50%">}}

### Vignettes

Please see these vignettes and articles about {eplusr}

* [Introduction to eplusr](https://hongyuanjia.github.io/eplusr/articles/eplusr.html)
* [Run simulation and data exploration](https://hongyuanjia.github.io/eplusr/articles/job.html)
* [Parametric simulations](https://hongyuanjia.github.io/eplusr/articles/param.html)
* [Update IDF version](https://hongyuanjia.github.io/eplusr/articles/transition.html)
* [Work with weather files](https://hongyuanjia.github.io/eplusr/articles/epw.html)
* [Work with Schedule:Compact objects](https://hongyuanjia.github.io/eplusr/articles/schedule.html)
* [Work with geometries](https://hongyuanjia.github.io/eplusr/articles/geom.html)
* [Frequently asked questions](https://hongyuanjia.github.io/eplusr/articles/faq.html)

### Slides

* [Slides: Interfacing EnergyPlus using R](https://hongyuanjia.github.io/eplusrIntro/)

### Additional resources

* eplusr manual: https://hongyuanjia.github.io/eplusr/
* eplusr Docker image: https://github.com/hongyuanjia/eplusr-docker
* [epwshiftr](https://cran.r-project.org/package=epwshiftr) for creating future
  EnergyPlus weather files using CMIP6 data
* [epluspar](https://github.com/hongyuanjia/epluspar) for conducting parametric
  analysis on EnergyPlus models, including sensitivity analysis, Bayesian
  calibration and optimization.

### Acknowledgement

This research is supported by the National Research Foundation, Prime Minister’s
Office, Singapore under its Campus for Research Excellence and Technological
Enterprise (CREATE) programme. It was funded through a grant to the Berkeley
Education Alliance for Research in Singapore (BEARS) for the Singapore-Berkeley
Building Efficiency and Sustainability in the Tropics (SinBerBEST) Program.
BEARS has been established by the University of California, Berkeley as a center
for intellectual excellence in research and education in Singapore.
