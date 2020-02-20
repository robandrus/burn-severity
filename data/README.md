|Variable (raw data)           |Clean name (if different)         |Description                                                                                                                                                                                                        |
|:-----------------------------|:---------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|`fire_year`                   |                                  |Calendar year of fire event                                                                                                                                                                                        |
|`FIRE`                        |                                  |4 letter code for fire name (see Appendix S1, Table S1 for full names)                                                                                                                                             |
|`plotname`                    |                                  |Unique plot name                                                                                                                                                                                                   |
|`PLOT`                        |                                  |Unique plot number                                                                                                                                                                                                 |
|`RdNBR`                       |                                  |Relative differenced Normalized Burn Ratio (Miller and Thode 2007)  value extracted from the focal pixel of each plot                                                                                              |
|`RdNBR_BL`                    |                                  |Relative differenced Normalized Burn Ratio (Miller and Thode 2007)  value extracted from the bilinear interpolation method from the 4 nearest neighboring cells for each plot                                      |
|`dNBR`                        |                                  |Differenced Normalized Burn Ratio (Key and Benson 2005) value extracted from the focal pixel of each plot                                                                                                          |
|`dNBR_BL`                     |                                  |Differenced Normalized Burn Ratio (Key and Benson 2005) value extracted from the bilinear interpolation method from the 4 nearest neighboring cells for each plot                                                  |
|`RBR`                         |                                  |Relative Burn Ratio (Parks et al. 2014a) value extracted from the focal pixel of each plot                                                                                                                         |
|`RBR_BL`                      |                                  |Relative Burn Ratio (Parks et al. 2014a) value extracted from the bilinear interpolation method from the 4 nearest neighboring cells for each plot                                                                 |
|`pre_NBR`                     |pre-fire NBR                      |Pre-fire Normalized Burn Ratio (Key and Benson 2005) value extracted from the focal pixel for each plot                                                                                                            |
|`lat`                         |latitude                          |Latitude (degrees) for each plot center                                                                                                                                                                            |
|`slope`                       |slope                             |Slope (degrees) measured at each plot center                                                                                                                                                                       |
|`HeatLoad`                    |Heat load index                   |Heat load (MJ cm-2 yr-1) value extracted from the focal pixel of each plot (McCune and Keon 2002)                                                                                                                  |
|`MaxTreeHeight`               |Max tree height                   |Height of the tallest tree in the plot, measured to the nearest 0.1 m using a TruePulse 360 TM laser rangefinder                                                                                                   |
|`QMD_LAF`                     |QMD (live at fire)                |Quadratic mean diameter, all trees (cm)                                                                                                                                                                            |
|`QMD_all`                     |QMD (live at fire)                |Quadratic mean diameter, trees live at fire (cm)                                                                                                                                                                   |
|`FIRESEVNUM`                  |                                  |Code that signifies if a plot was burned or unburned; > 0 designates burned                                                                                                                                        |
|`CHARHT_percMax`              |Char height                       |Average proportion of total tree height that was charred from randomly selected dominant canopy trees (20/plot) that were alive at the time of fire.                                                               |
|`BOLESCORCH`                  |Bole scorch                       |Average proportion of tree bole circumference that was charred from randomly selected dominant canopy trees (20/plot) that were alive at the time of fire. This value was the maximum % at any height on the bole. |
|`CHARCOV`                     |Charred surface cover             |Average proportion of charred ground cover in plots, taken from 480-500 points > 10 cm apart along the main plot axis (N-S, E-W).                                                                                  |
|`Firemort.BA.p`               |Basal area killed by fire         |The proportion of tree basal area per plot that was alive at the time of fire and killed by the fire.                                                                                                              |
|`Firemort.trees.p`            |Trees killed by fire              |The proportion of trees per plot that were alive at the time of fire and killed by the fire.                                                                                                                       |
|`ba_ha`                       |stand basal area                  |Basal area (m2/ha)                                                                                                                                                                                                 |
|`stems_ha`                    |stand density                     |Stand density (stems/ha)                                                                                                                                                                                           |
|`RedGrayGreenStage.BA.p`      |pre-fire beetle outbreak severity |Beetle-killed basal area, trees killed pre-fire (proportion of BA in stand)                                                                                                                                        |