# Atmo DNN (Deep Neural Network)

### _Atmo DNN_ is a deep learning model built **from scratch**. 

Its main objective is to determine the atmospheric conditions/chemical composition of planets and stars. It aims to understand the conditions necessary to support life.


## Data Source 📊
Utilizes the [NASA Frontier Development Labs (FDL) PSG/INARA Dataset](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/FDL/nph-fdl?psg)


## Atmospheric Conditions of Planet 
This part of the model focuses on determining the chemical composition of the planet's atmosphere.

### Inputs
**Inputs**:
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

**Outputs**:
- CH4 abundance	(fractional)
- N2O abundance	(fractional)
- CO abundance (fractional)
- O3 abundance (fractional)
- SO2 abundance	(fractional)
- NH3 abundance	(fractional)
- C2H6 abundance (fractional)
- NO2 abundance (fractional)

---

## Installation & Deployment 🚀

To set up the environment for running this project, especially with Jupyter notebooks, follow the steps below:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/DorsaRoh/Atmo-DNN.git
    cd Atmo-DNN
    ```

2. **Install Necessary Packages**:
    ```bash
    pip install jupyter pandas tensorflow numpy scikit-learn matplotlib seaborn
    ```

    or 

    ```bash
    pip install -r requirements.txt
    ```

3. **Run Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

Now, you can navigate to the desired notebook and run the cells.

---

## Contributing 🤝
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/DorsaRoh/Atmo-DNN/issues).

---

## License 📝
Distributed under the MIT License. See `LICENSE` for more information.

---

## Contact 📩
dorsa.rohani@gmail.com

Project Link: [https://github.com/DorsaRoh/Atmo-DNN](https://github.com/DorsaRoh/Atmo-DNN)
