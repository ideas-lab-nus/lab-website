+++
title = "Calibrating building simulation models using multi-source datasets and meta-learned Bayesian optimization"
date = 2022-07-15
authors = ["Sicheng Zhan", "Gordon Wichern", "Christopher Laughman", "Adrian Chong", "Ankush Chakrabarty"]
publication_types = ["2"]
abstract = """
Reliable building simulation models are key to optimizing building performance and reducing greenhouse gas emissions. Informed decision making requires simulation models to be accurate, extrapolatable, and interpretable, all of which require calibrating model simulations to ground truth. Complicated building dynamics and highly uncertain exogenous disturbances make the model calibration process challenging and expensive; hence, a scalable and efficient calibration approach is needed to enable actual application. Current automatic calibration algorithms do not leverage data collected from multiple sources: for example, data obtained from previous calibration tasks on other buildings. In this paper, we employ probabilistic deep learning to meta-learn a distribution using multi-source data acquired during previous calibration. Subsequently, the meta-learned Bayesian optimizer accelerates calibration of new, unseen tasks. The few-shot (that is, requiring few model simulations) nature of the proposed algorithm is demonstrated on a Modelica library of residential buildings validated by the United States Department of Energy (USDoE). The proposed algorithm is compared against classical Bayesian optimization-based calibration, and it is shown that ANP significantly sped up the calibration procedure: the optimal model parameters are identified with 40–60% less simulations compared to the baseline.
"""
featured = false
publication = "Energy and Buildings"
tags = ["Meta learning", "Deep learning", "Parameter estimation", "Probabilistic machine learning", "Bayesian methods", "Digital twin"]


doi = "10.1016/j.enbuild.2022.112278"

+++

