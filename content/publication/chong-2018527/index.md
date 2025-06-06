+++
title = "Guidelines for the Bayesian calibration of building energy models"
date = 2018-01-01
authors = ["Adrian Chong", "Kathrin Menberg"]
publication_types = ["2"]
abstract = "This paper provides practical guidelines to the Bayesian calibration of building energy models using the probabilistic programming language Stan. While previous studies showed the applicability of the calibration method to building simulation, its practicality is still impeded by its complexity and the need to specify a whole range of information due to its Bayesian nature. We ease the reader into the practical application of Bayesian calibration to building energy models by providing the corresponding code and user guidelines with this paper. Using a case study, we demonstrate the application of Kennedy and O’Hagan’s (KOH) [1] Bayesian calibration framework to an EnergyPlus whole building energy model. The case study is used to analyze the sensitivity of the posterior distributions to the number of calibration parameters. The study also looks into the influence of prior specification on the resulting (1) posterior distributions; (2) calibrated predictions; and (3) model inadequacy that is revealed by a discrepancy between the observed data and the model predictions. Results from the case study suggest that over-parameterization can result in a significant loss of posterior precision. Additionally, using strong prior information for the calibration parameters may dominate any influence from the data leading to poor posterior inference of the calibration parameters. Lastly, this study shows that it may be misleading to assume that the posteriors of the calibration parameters are representative of their true values and their associated uncertainty simply because the calibrated predictions matches the measured output well."
featured = false
publication = "*Energy and Buildings*"
tags = ["Bayesian calibration", "Building energy modeling", "Building simulation", "Gaussian process", "Hamiltonian Monte Carlo"]
url_pdf = "publication/pdf/chong-2018527.pdf"
doi = "https://doi.org/10.1016/j.enbuild.2018.06.028"
+++

