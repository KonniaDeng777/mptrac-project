# Tracking Carbon Dioxide with Lagrangian Transport Simulations:Case Study of Canadian Forest Fires in May 2021

**Abstract:** The large amounts of greenhouse gases, such as carbon dioxide, produced by severe forest fires not only seriously affect the ecosystems in the area where the fires occur but also cause a greenhouse effect that has a profound impact on the natural environment in other parts of the world. Numerical simulations of greenhouse gas transport processes are often affected by uncertainties in the location and timing of the emission sources and local meteorological conditions, and it is difficult to obtain accurate and credible predictions by combining remote sensing satellite data with given meteorological forecasts or reanalyses. To study the regional transport processes and impacts of greenhouse gases produced by sudden large-scale forest fires, this study applies the Lagrangian
particle dispersion model Massive-Parallel Trajectory Calculations (MPTRAC) to conduct forward simulations of the CO2 transport process of greenhouse gases emitted from forest fires in the central region of Saskatchewan, Canada, during the period of 17 May to 25 May 2021. The simulation results are validated with the Orbiting Carbon Observatory-2 Goddard Earth Observing System (OCO-2 GEOS) Level 3 daily gridded CO2 product over the study area. In order to leverage the high computational costs of the numerical simulations of the model, we implement the forward simulations on the Tianhe-2 supercomputer platform and the JUWELS HPC system, which greatly improves the computational efficiency through parallel computation and makes near-real-time predictions of atmospheric transport processes feasible.

**Keywords:** forest fires; carbon dioxide; Lagrangian transport simulations; MPTRAC; OCO2

**Paper link:** https://doi.org/10.3390/atmos15040429

**Reference:** https://github.com/slcs-jsc/mptrac

![fig1](fig1.png)
![fig2](fig2.png)
Figure. Maps of CO2 distribution from the Canadian forest fire. (a) Simulation results of MPTRAC. (b) Anomalies calculated from the NASA OCO-2 Level 3 assimilated data product. The red triangle indicates the particle source term position.
