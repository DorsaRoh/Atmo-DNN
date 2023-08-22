# isLife
### Determines the conditions of a planet; conditions needed to support life.

A collection of **deep learning** and **machine learning models** that predict and determine a planet/exoplanet's potential to sustain life based on the criteria below:

1. Predicting atmospheric conditions of planet
2. Predicting quality of liquid water, if present
3. Predicting the stability of climate
4. Predicting the presence of a magnetic field
5. Predicting planet's distance from its host star

The above are the general encompassing requirements for a planet to sustain carbon-based life.
<i>"isLife == true ? isLife == false"</i>


## Data

Atmospheric Conditions: [NASA Frontier Development Labs (FDL) PSG/INARA Dataset](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/FDL/nph-fdl?psg)

H2O Quality: [Kaggle, Water Potability](https://www.kaggle.com/datasets/adityakadiwal/water-potability)


## 1. Atmospheric Conditions of Planet

Determines the chemical composition of the planet's atmosphere.

- Inputs: 
    - Semi-Major Axis (AU)
    - Planet Radius	(km)
    - Planet Density (g/cm3)
    - Planet Surface Pressure (bar)
    - kappa	(fractional)
    - gamma1 (fractional)
    - gamma2 (fractional)
    - alpha	beta (fractional)
    - Planet Surface Temperature (K)
    - Avg Mol Weight (fractional)
    - Mean Surface Albedo (fractional)

- Outputs:
    - CH4 abundance	(fractional)
    - N2O abundance	(fractional)
    - CO abundance (fractional)
    - O3 abundance (fractional)
    - SO2 abundance	(fractional)
    - NH3 abundance	(fractional)
    - C2H6 abundance (fractional)
    - NO2 abundance (fractional)


## 2. Presence of Liquid Water

Determines the potability of the water, if present, on the planet.

- Inputs:
    - ph: pH of 1. water (0 to 14)
    - Hardness: Capacity of water to precipitate soap (mg/L)
    - Solids: Total dissolved solids (ppm)
    - Chloramines: Amount of Chloramines (ppm)
    - Sulfate: Amount of Sulfates dissolved (mg/L)
    - Conductivity: Electrical conductivity of water (μS/cm)
    - Organic_carbon: Amount of organic carbon (ppm)
    - Trihalomethanes: Amount of Trihalomethanes (μg/L)
    - Turbidity: Measure of light emiting property of water (NTU)

- Outputs:
    - Potability: Indicates if water is safe for human consumption. Potable 1 and Not potable 0
