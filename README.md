# Degradation_Code

# Degraded Carbon Modeling
Degraded Carbon Modeling (DCM) is a Google Earth Engine (GEE) cloud-based script compendium for estimating forest degradation using Landsat sensor data (L5, L7, and L8) and field data from forest inventories.

DCM uses spectral mixture models for mapping forest degradation. The study was developed to estimate forest degradation in the pine forests of the Dominican Republic. The study can be cited as “Duarte E, Barrera JA, Dube F, Casco F, Alexander AJ, Zagal E. Monitoring approach for tropical coniferous forests degradation using remote sensing and data field. 2020”

The complete model contains 10 steps that must be applied in the order indicated.



# Pre-processing 

Step 1. Cloud-free composite mosaic. https://code.earthengine.google.com/59d2e5ea1460cc94c17ba3b7e328203d

Step 2. Topographic correction. https://code.earthengine.google.com/b5c04df93dbfa9704196a2d70ef89008



# Dynamic land change cover analysis

Step 3. Dynamic land cover change analysis (stable forest, stable non-forest, deforestation and forest restored).
https://code.earthengine.google.com/0c477166d32a49483b630615bbf144f4

Step 4. Degradation analysis (stable forest and forest degraded).
https://code.earthengine.google.com/d0e36ff232471f10dcf9f503a2bc69c3

Step 5. Dynamic land cover change final (stable forest, stable non-forest, deforestation, forest restored and forest degraded). 
https://code.earthengine.google.com/bd193a622a94bf1e1abe273d92a25c4a



# Modeling

Step 6. Change magnitude.
https://code.earthengine.google.com/26905ece22e44b9d3b9bd59b6037f3b5

Step 7. Carbon modeling.
https://code.earthengine.google.com/6749589abc3ec9377b49926b43eb663c



# Accuracy assessment

Step 8. Spectral indices
https://code.earthengine.google.com/57254f336d87fc09de2b83e1d309feb8

Step 9. Landsat Time Series 
https://code.earthengine.google.com/26a24f91678b422f90974d0451dd7fe9

Step 10. Landsat Time Series viewer
https://code.earthengine.google.com/de48df568f425973a85673aa6651cb8d



