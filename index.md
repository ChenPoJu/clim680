---
layout: default
title: CLIM-680 project
description: Po Ju Chen
---
# The importance of modifying aerosols in Miocene Simulations

### Motivation
1. Past climate states are different from today and provide evidences of how climate processes operated across states that span the range of CO<sub>2</sub>  concentrations (400~2000 ppm) associated with future emissions scenarios. _(Tierney et al. 2020)_

2. The latest generation of climate models with state-of-the-art parameterizations of cloud micro-physics and cloud-aerosol interactions raised the issue of dust and aerosol effects in Paleoclimate simulation. _(Sagoo & Storelvmo, 2017)_

3. PlioMIP (Pliocene Model Intercomparison Project) provided us a chance to improve our understanding of climate sensitivity and environmental consequences under the scenario of atmospheric CO<sub>2</sub>  concentration near 400 ppm. _(Haywood et al. 2016; Haywood et al. 2020)_
   - More temporally consistent boundary conditions and forcings are used within models. (ex: land-ice surface topography, ocean bathymetry, land surface cover etc.)
   - Pre-industrial aerosols are prescribed in their simulations

4. The research in Miocene, an epoch when the earth had higher CO<sub>2</sub>  concentration, less ice sheet, and larger continental greening than Pliocene, is still in progress.

(1) _What are the dust and aerosols effects in Miocene simulations?_

(2) _Whether the modification of prescribed aerosols is critical in paleoclimate simulations?_

### Experimental Design
<img width="982" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/82ab9d72-0028-4a83-bd6d-ea9298253986">

* Modified aerosols _(Heaven et al. 2014)_

<img width="323" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/ad88578d-5eaf-4600-b972-0a0622443da7">

* Modified aerosols in our cases

1. DMS modification (Mio_Pi v.s. Mio_Mio)
<img width="634" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/d441dfdc-f4af-419b-ad25-2d0779ea7ef3">

2. Modified Dust: unify the dust erodibility in Mio_Mio with vegetation condition (Mio_Pi v.s. Mio_Mio)
<img width="907" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/aa8aedee-2931-43b6-b064-e07c8ac11112">

3. Modified Aerosols (ex: Black Carbon)
<img width="584" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/3f101704-276b-464b-8821-017822aedc58">


### Results & Code Description
* [Patterns in Climatology](./doc/Patterns.html)
* [Composite Precipitation & TS based on Dust Indices](./doc/CompositePrecTS.html)
* [Correlation Dust & Precipitation](./doc/Correlation.html)
* [Composite Aerosols based on Dust Indices](./doc/CompositeAerosols.html)
* [ENSO in Miocene simulations](./doc/ENSO.html)

### Summary
1. Modifying dust and aerosol emissions makes the surface temperatue in the Miocene simulation warmer in High Latitude and north-east Pacific.
   - Warming in the north-east Pacific is associated with cloud-related shortwave influx.
2. Modification of dust emission decreases the amount and the variation of dust in the Middle East and the North America, but increases the amount and variation in the South America.
   - Composite patterns show consistent decreased/increased precipitation and warming/cooling during the months when dust is high/low. However, the composite patterns based on Index3 (Dust in South America), which has less order and variation of dust amount.
3. Correlation between dust indices and precipitation is hard to explain and is mostly not statistically significant.
   - Composite precipitation patterns tell us that the modified dust emission might be critical to the resulting precipitation.
   - However, the correlation maps suggest that the dust may not directly related to the precipitation.
   - Or, the dust concentration is partially modulated by precipitation
4. Composite patterns of Black Carbon could partially explain the composite precipitation and TS, but the composite sulfate cannot.

#### [Reference](./doc/Reference.html)
