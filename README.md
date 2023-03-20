# Austraila_heat-air-health_GWRF
This repository is for paper "Unpacking the inter- and intra-urban disparity of the effect of heat and air quality on health in Australia ". [paper link](https://doi.org/10.1016/j.scitotenv.2023.162005)

The Local Geographical Weighted Random Forest Model was employed to explore the importance of heat and air quality to physical and mental health in Australia referring to [Geographical random forests: a spatial extension of the random forest algorithm to address spatial heterogeneity in remote sensing and population modelling](https://www.tandfonline.com/doi/full/10.1080/10106049.2019.1595177). Geographical Weighted Random Forest (GRF) is based on the concept of spatially varying coefficient models (Fotheringham et al. 2003) where a global process becomes a decomposition of several local sub-models and can be used as a predictive and/or explanatory tool. The code are based on R and set Melbourne as example [localGWRF_mel](https://github.com/WenhuiCaii/Austraila_heat-air-health_GWRF/blob/main/localGWRF_Mel.Rmd).

The local R2 map of Melbourne with mental health as independent variable is:

![image](https://github.com/WenhuiCaii/Austraila_heat-air-health_GWRF/blob/main/localR2.jpeg)

The local importance map of heat of Melbourne with mental health as independent variable is:

![image](https://github.com/WenhuiCaii/Austraila_heat-air-health_GWRF/blob/main/importance.temperatur.jpeg)

In this study, the Global GWRF Models were based on urban and rural dataset instead of cities and the ALE analysis was applied to model results. For ALE plots generating code, please referring [ RF and ALE.ipynb](https://github.com/WenhuiCaii/Australian-heatwave-study/blob/main/RF%20and%20ALE.ipynb).

The ALE plot of temperature in urban GWRF Model with mental health as independent variable is: 

![image](https://github.com/WenhuiCaii/Austraila_heat-air-health_GWRF/blob/main/temperature.jpg)
