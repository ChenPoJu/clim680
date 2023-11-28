---
layout: default
title: Correlation
description: Dust Indices  v.s.  Precipitation
---
* variable: BURDENDUST [kg/m2]
  - Dust aerosol burden --- total concentration of dust per meter square over a grid
<img width="612" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/df4cd4f7-da8a-47ac-972f-8a818d58a46b">

* **(High / Low)**: the months when the amount of dust is over / under 2 times standard deviation
<img width="780" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/cf2253e0-bf66-477b-a567-a42bfed43b3f">

> **Examining Correlation between Dust Indices & Precipitation**: I do not calculate it in the whole time series. I only calculate their correlation in the months when the dust index is high or low. _(ex: If there are 48 months when index1 is high, I calculate the correlation between dust index1 & precipitation in those 48 months)_

## (1) **Index 1**: (50-90E; 20-50N)
<img width="714" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/0ef28d63-354b-46f4-906b-1ca87c556faa">

## (2) **Index 2**: (100-80W; 30-45N)
<img width="910" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/9e6345b3-c8cc-43b8-9232-00b31817de80">

## (3) **Index 3**: (75-55W; 15-45S)
<img width="906" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/a882c7d1-5bbe-4ba1-b82a-70d51bda4715">

* The correlation maps are not consistent with composite precipitation patterns for each index
* Most of correlation maps are not statistically significant:
  - Composite precipitation patterns tell us that the modified dust emission might be critical to the resulting precipitation.
  - However, the correlation maps suggest that the dust may not directly related to the precipitation.
  - Or, the dust concentration is partially modulated by precipitation

<iframe src="https://nbviewer.org/github/ChenPoJu/clim680_project/blob/master/Project/Dust_correlation.ipynb" width="800" height="600"></iframe>


[Composite Aerosols based on Dust Indices](./CompositeAerosols.html)

[Main Context](../)
