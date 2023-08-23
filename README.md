# Atmo DNN (deep neural network)
### Deep learning model created from scratch
### Determines the atmospheric conditions/chemical composition of a planets and stars; conditions needed to support life.

### Data

[NASA Frontier Development Labs (FDL) PSG/INARA Dataset](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/FDL/nph-fdl?psg)

## 1. Atmospheric Conditions of Planet

Determines the chemical composition of the planet's atmosphere.

- Inputs:
- 
    - Planetary:
        - Semi-Major Axis (AU)
        - Planet Radius	(km)
        - Planet Density (g/cm3)
        - Planet Surface Pressure (bar)
    - Stellar:
        - Stellar Type
        - Stellar Temperature
        - Stellar Radius
          
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
