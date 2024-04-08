# Atmo

### _Atmo_ is a deep learning model built **from scratch**. 

Its main objective is to determine the atmospheric conditions/chemical composition of planets and stars. Aims to identify exoplanets with conditions supportive of carbon-based life, and explore other means of determining chemical compositions of atmospheres without light.

<br>
<div align="center">
    <img src="https://github.com/DorsaRoh/Atmo-DNN/blob/main/assets/diagram.png" width="400">
</div>
<br>

## Accuracy 📊
Planetary Model: 91.33% <br>
Stellar Model: 96.43%

## Data 
Utilizes the [NASA Frontier Development Labs (FDL) PSG/INARA Dataset](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/FDL/nph-fdl?psg)


## Atmospheric Conditions of Planet 
This part of the model focuses on determining the chemical composition of the planet's atmosphere.

### Inputs
**Inputs (features)**:
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
- Surface Temperature (K)
- Avg Mol Weight (fractional)
- Mean Surface Albedo (fractional)

**Outputs (targets)**:
- CH4 abundance	(fractional)
- N2O abundance	(fractional)
- CO abundance (fractional)
- O3 abundance (fractional)
- SO2 abundance	(fractional)
- NH3 abundance	(fractional)
- C2H6 abundance (fractional)
- NO2 abundance (fractional)

## Model Architecture 📐

_Atmo DNN_ utilizes a deep learning architecture that includes the following layers:

1. **Input Layer**: 12 neurons.
2. **Hidden Layer 1**: 128 neurons.
3. **Hidden Layer 2**: 64 neurons.
4. **Hidden Layer 3**: 32 neurons.
5. **Output Layer**: 12 neurons.

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
