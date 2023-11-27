---
layout: default
title: Composite Precipitation & Surface Temperature
description: Based on Dust Indices
---
> **Question**: What are the composite precipitation and surface temperature patterns when concentrations of dust are high or low in some regions? 

## Detemining Dust indices
* variable: BURDENDUST [kg/m2]
  - Dust aerosol burden --- total concentration of dust per meter square over a grid
<img width="612" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/df4cd4f7-da8a-47ac-972f-8a818d58a46b">

## Defining High/Low Dust months
* **(High / Low)**: the months when the amount of dust is over / under 2 times standard deviation
<img width="780" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/cf2253e0-bf66-477b-a567-a42bfed43b3f">

* Modifying Input Dust in Mio_Mio increases the variation of dust concentration over the regions of index1 & index2, but decreases the variation of index3

## Composite Patterns based on Dust Indices 
### (1) Precipitation 
<img width="655" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/31f149e3-82c5-43b9-9c46-9530f13ccc1b">

* consistent decreased/increased precipitation during the months when dust is high/low (except: index 3)

### (2) Temperature (TS)
<img width="646" alt="image" src="https://github.com/ChenPoJu/clim680_project/assets/142943588/00fa0d39-ae94-4f8a-ba55-e27c24777ce2">

* consistent warming/cooling during the months when dust is high/low (except: index3)

<iframe src="https://nbviewer.org/github/ChenPoJu/clim680_project/blob/master/Project/Dust_composite_PrecTS.ipynb" width="800" height="600"></iframe>

[Main Context](../)
