# isLife
### Determines the conditions of a planet; conditions needed to support life.

A collection of deep learning and machine learning models that predict and determine a planet/exoplanet's potential to sustain life based on the criteria below:

1. Predicting atmospheric conditions of planet
2. Predicting quality of liquid water, if present
3. Predicting the stability of climate
4. Predicting the presence of a magnetic field
5. Predicting planet's distance from its host star

The above are the general encompassing requirements for a planet to sustain carbon-based life.
<i>"isLife == true ? isLife == false"</i>


## Data

Atmospheric Conditions: ![NASA Frontier Development Labs (FDL) PSG/INARA Dataset](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/FDL/nph-fdl?psg)

H2O Quality: https://www.kaggle.com/datasets/adityakadiwal/water-potability


## 1. Atmospheric Conditions of Planet

- Inputs: 
    - Semi-Major Axis	
    - Planet Radius	
    - Planet Density	
    - Planet Surface Pressure	
    - kappa	
    - gamma1	
    - gamma2	
    - alpha	beta	
    - Planet Surface Temperature
    - Avg Mol Weight	
    - Mean Surface Albedo

- Outputs:
    - CH4 abundance	
    - N2O abundance	
    - CO abundance	
    - O3 abundance	
    - SO2 abundance	
    - NH3 abundance	
    - C2H6 abundance	
    - NO2 abundance	


## 2. Presence of Liquid Water
