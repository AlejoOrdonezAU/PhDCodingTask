# Interview Question for the PhD Project

## "Forecasting the Near-Future Spread of Novel Ecosystems under Alternative Environmental Scenarios"

This modelling-focused PhD project will develop computationally intensive, high-resolution global forecasts of the near-future Novel Ecosystem (NE) spread and assess the resulting impacts on biodiversity and climate-related ecosystem functions. 

### Question:
Imagine you are tasked with developing a model to simulate the future distribution of a specific vegetation type (biome) from a set of 14 global biomes. This model should be based on key environmental variables such as:
- Short-wave and photosynthetically active solar radiation (e.g., estimated based on the Earth's position)
- Atmospheric CO₂ concentration
- Mean monthly climate parameters (e.g., precipitation, temperature, percent sunshine)
- Soil physical properties (e.g., water-holding capacity, percolation rate)

Using this model, focus on answering the following questions:

1. **What computational methods did you use to build your model?**
2. **How did you approach designing such a model?**
3. **How would you evaluate the accuracy and quality of your model predictions?**
4. **Given the predicted present-day biome distributions, how would you assess the differences between contemporary patterns and those projected in the future?**
5. **What challenges do you foresee in modeling biome shifts over long-term time frames, and how would you address them?**

This question aims to assess your understanding of ecological modeling, paleoenvironmental reconstructions, and computational approaches in biogeography.

### Provided Data
You will receive:
- A **Shapefile** with the world's biomes (`wwf_Biomes.*`)
- A **NetCDF file** (`BIOME4_inputdata.nc`) containing today's environmental conditions

### Variables in the NetCDF File:

| Short Name | Long Name | Units |
|------------|------------|------------|
| `temp_*` | Monthly mean temperature (Number indicates the month of the year) | °C |
| `prec_*` | Monthly total precipitation (Number indicates the month of the year) | mm |
| `sun_*` | Mean monthly percent of possible sunshine (Number indicates the month of the year) | % |
| `whc_soil_layer_*` | Soil water holding capacity (Layer=1: 0-30cm; Layer=2: 30cm-bottom) | mm/m |
| `perc_soil_layer_*` | Soil water percolation index (Layer=1: 0-30cm; Layer=2: 30cm-bottom) | mm/hr |
| `tmin` | Annual absolute minimum temperature | °C |
