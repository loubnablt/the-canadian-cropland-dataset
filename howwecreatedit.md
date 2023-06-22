---
layout: default
title: The Canadian Cropland Dataset
---

<h1 style="text-align: center;"> How we created it </h1>

### Image and Label Collection

___


### Data Cleaning

___


### Dataset Statistics 

___

### Features  


| Index | Description |
|-------|-------------|
| NDVI  | Indicator of plant growth and health, measures emitted chlorophyll |
| NDVI45| Indicates the amount of biomass and evapotranspiration, provides information on canopy structure |
| GNDVI | Correlates to the rate of photosynthesis, used to monitor plant stress |
| PSRI  | Measures the onset, the stage, and the relative rates of the senescence or ripening of a crop cover |  
| OSAVI | Provides an estimate of biomass that is more resilient when faced with soil and atmospheric effects |   



- **NDVI** The *Normalized Difference Vegetation Index* is one of the most predominantly used indicators of plant growth and health. It correlates with the amount of chlorophyll emitted by a plant. NDVI is defined as:  

     *NDVI = (ρ<sub>NIR</sub> - ρ<sub>red</sub>) / (ρ<sub>NIR</sub> + ρ<sub>red</sub>)*  
     
Where ρ<sub>NIR</sub> is equal to the NIR band and ρ<sub>red</sub> is the visible red band.


- **NDVI45** The *NDV45* vegetation index is a revised version of the NDVI. It is strongly correlated with the leaf area index (LAI), which is an estimate of the amount of biomass and vegetative evapotranspiration, and provides information regarding the structure of a canopy. NDVI45 is defined as:  

     *NDVI45 = (R<sub>704</sub> - ρ<sub>red</sub>) / (R<sub>704</sub> + ρ<sub>red</sub>)*  

Where R<sub>704</sub> is the NIR spectral band centered at 704 nm.  

- **GNDVI** The *Green Normalized Difference Vegetation Index* was shown to correlate to the rate of photosynthesis and is used to monitor plant stress. GNDVI is calculated in a way that is analogous to NDVI, however the red band is replaced by the green band (ρ<sub>green</sub>). GNDVI is defined as:  

     *GNDVI = (ρ<sub>NIR</sub> - ρ<sub>green</sub>) / (ρ<sub>NIR</sub> + ρ<sub>green</sub>)*  

- **PSRI** The *Plant Senescence Reflectance Index* is used to measure the onset, the stage, and the relative rates of the senescence or ripening of a crop cover. An increase in PSRI indicates heightened canopy stress. PSRI is defined by the equation:  

     *PSRI = (ρ<sub>red</sub> - ρ<sub>blue</sub>) / R<sub>750</sub>*  

Where R<sub>750</sub> is the NIR spectral band centered at 750 nm.  

- **OSAVI** In conditions when vegetation is low and soil properties are unknown, indices like the NDVI can be subject to bias due to high levels of reflection. The *Optimized Soil-Adjusted Variation Index* was created to provide an estimate of biomass that is more resilient when faced with soil and atmospheric effects. OSAVI is defined as:  

     *OSAVI = (ρ<sub>NIR</sub> - ρ<sub>red</sub>) / (ρ<sub>NIR</sub> + ρ<sub>red</sub> + 0.16)*  

