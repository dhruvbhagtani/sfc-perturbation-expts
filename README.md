# varying-surface-forcing
The ocean circulation is driven by a combination of winds and surface buoyancy fluxes. We run a number of experiments with varied surface forcings and look at the spatial variations in ocean circulation on short and long time-scales. 

## List of potential experiments 

| Name of experiment      | Description | Issues | References |
| :---:                   |  :---:      |  :---: |  :---:     |    
| Zero mean winds    | Removing the time-mean winds and inputting only the temporal fluctuations. It is believed that the ocean gyres receive momentum input from the mean winds. A contradictory theory (refer Chris Bull's paper) also highlights the role of wind variability in determining the strength of western boundary currents in ocean gyres.            |    a. Should we alter the mean winds or mean wind stress for this experiment? <br /> b. As a follow up to (a), the ACCESS-OM2 uses relative winds to estimate wind stress, which is the difference between absolute winds and ocean surface velocities. Removing mean winds wouldn't necessarily imply that all time fluctuations in wind stresses are removed. | Chris Bull 2018 |
| Altering surface buoyancy forcing    | In the past, our experiments focused on altering wind stress in ocean basins. However, winds affect a lot of ocean dynamics which could have an adverse effect on surface buoyancy forcing as well. Therefore, instead of changing the magnitude of wind stress, we change the magnitude of surface buoyancy forcing and study the resulting effect on ocean circulation. We can change (block/permit) the heat fluxes entering the ocean in various ways, like (i) Altering the bulk formulae, (ii) Changing KPP and (iii) Perturbing the SAT (Surface air temperature).  | a.   | |
| Altering wind stress magnitude    | In the past, our experiments focused on altering wind stress in ocean basins. However, winds affect a lot of ocean dynamics which could have an adverse effect on surface buoyancy forcing as well. Therefore, instead of completely shutting down winds, we can tinker (strengthen/weaken winds by 20-30%). We can use the spatial mask already coded in ACCESS-OM2 for our purpose.  | a.   | |
| Manual tweaking of KPP depth                   |        |   |       |  
| Winds off in specific basins                   |        |   |       |  
| Winds off in [50 S, 50 N]                   |        |   |       |  
