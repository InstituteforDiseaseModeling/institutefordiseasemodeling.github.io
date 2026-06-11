# Institute for Disease Modeling

IDM's goal is to support global efforts to eradicate infectious diseases and achieve permanent improvements in health by developing, using, and sharing computational modeling tools and promoting quantitative decision-making.

All software tools that IDM builds and provides to the broader global health community are listed below.

## Modeling frameworks

IDM provides three broad frameworks for modeling disease transmission, each of which contain models for specific diseases or health conditions.


<div class="grid cards" markdown>

-   :material-language-python:{ .lg .middle } __Starsim__{ #starsim } 

    --- 

    The Starsim framework is used for examining the spread of infectious disease in situations when the details of how an individual's immune system, and heterogeneity across immune systems, changes the answer to a particular research question. Use Starsim models when within-host biology, co-infection, or fine-grained intervention effects matter.

    Best suited for: HIV, TB, STIs, HPV, Family Planning, and other questions where individual-level details shape population dynamics.

    [:octicons-arrow-right-24: Starsim](https://starsim.idmod.org)

-   :material-language-python:{ .lg .middle } __LASER__{ #laser } 

    ---

    The LASER (Light Agent Spatial modeling for ERadication) framework is especially suited for modeling disease transmission where spatial connectivity and heterogeneity matters. Geographic location, human movement patterns, and the specifics of disease transmission dynamics are combined to answer questions about locations and populations most at risk.

    Best suited for: spatial spread, meta-population models, and large-population campaigns such as polio eradication or evaluation of vaccination campaigns.

    [:octicons-arrow-right-24: LASER](https://laser.idmod.org)

-   :material-language-cpp:{ .lg .middle } __EMOD__{ #emod } 

    ---

    EMOD (Epidemiological MODeling software) is IDM's longest-running modeling framework, designed for diseases where both individual traits or behaviors and regional context are important for transmission. It is especially well-developed for malaria, with detailed components for mosquito life cycles, climate, and malaria-specific interventions. EMOD is no longer actively maintained but remains available to use.

    Best suited for: malaria eradication strategy evaluations, vector control, and regional campaign planning.

    [:octicons-arrow-right-24: EMOD](https://emod.idmod.org)

</div>

## Additional software tools

Outside of the three modeling frameworks above, we also provide the following software packages and dashboards.

### Packages

<div class="grid cards" markdown>

-   :material-language-python:{ .lg .middle } __historymatching__{ #history-matching } 

    ---

    historymatching is a Python implementation of the Bayesian history matching algorithm for model calibration and uncertainty quantification. History matching iteratively constrains a model's parameter space by comparing simulation outputs against observed data through statistical emulators. It is particularly useful for calibrating expensive computational models where exhaustive parameter sweeps are impractical.

    [:octicons-arrow-right-24: historymatching](https://docs.idmod.org/historymatching)

-   :material-language-python:{ .lg .middle } __idmtools__{ #idmtools } 

    ---

    idmtools is a collection of Python scripts and utilities designed to streamline interactions with disease modeling workflows. It can be used to run simulations on various platforms, including COMPS, Slurm, and Docker containers.

    [:octicons-arrow-right-24: idmtools](https://docs.idmod.org/idmtools)

-   :material-language-python:{ .lg .middle } __idmtools-calibra__{ #idmtools-calibra } 

    ---

    idmtools-calibra is an iterative parameter calibration framework for epidemic and scientific models. It repeatedly samples the parameter space, runs simulations via idmtools on COMPS, Slurm, and Docker container platforms, compares output to reference data, and updates the sampling strategy until convergence.

    [:octicons-arrow-right-24: idmtools-calibra](https://docs.idmod.org/idmtools-calibra)

-   :material-language-r:{ .lg .middle } __WES__{ #wes } 

    ---

    The WES R package provides reproducible functions for collating and analyzing data from wastewater and environmental sampling studies. Wastewater and environmental sampling (WES) of infectious diseases involves collecting samples from various sources (such as sewage, water, air, soil, or surfaces) to monitor the presence of pathogens in the environment. The package includes tools that assist with establishing standardized WES data formats to simplify data ingestion.

    [:octicons-arrow-right-24: WES](https://www.r-wes.com/)

-   :material-language-python:{ .lg .middle } __RAINIER__{ #rainier }

    ---

    RAINIER is a statistical approach for fitting SEIR epidemic models to case and mortality data. We used the approach to create models of COVID-19 transmission in King County, WA.

    [:octicons-arrow-right-24: RAINIER](https://github.com/InstituteforDiseaseModeling/kingcounty_rainier)

</div>

### Dashboards

<div class="grid cards" markdown>

-   :material-view-dashboard:{ .lg .middle } __Gene Drive__{ #gene-drive } 

    ---

    The Gene Drive dashboard enables you to explore the effects of a single release of gene drive mosquitoes with different values of various gene drive system and vector population parameters on malaria elimination probabilities and prevalence, as well as vector populations and genetics.

    [:octicons-arrow-right-24: Gene Drive](http://gene-drive.bmgf.io/)

-   :material-view-dashboard:{ .lg .middle } __HIV Leaky Vaccine__{ #leaky-vaccine } 

    ---

    The Leaky Vaccine dashboard is an online tool to explore the effects of exposure heterogeneity on HIV vaccine efficacy, given a leaky vaccine.

    [:octicons-arrow-right-24: HIV Leaky Vaccine](http://leakyvaccine.bmgf.io)

-   :material-view-dashboard:{ .lg .middle } __Subnational Family Planning Estimation Tool__{ #sfpet } 

    --- 

    The Subnational Family Planning Estimation Tool (SFPET) is an interactive web app created to aid policymakers in assessing progress towards family planning goals by visualizing both model-based and direct survey estimates of family planning indicators at the subnational level.

    [:octicons-arrow-right-24: SFPET](http://sfpet.bmgf.io)

</div>

