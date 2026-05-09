## Viscoelastic Characterization of Medical Tape Using the Standard Linear Solid Model

This project investigates the viscoelastic behavior of a medical tape specimen using creep and stress relaxation experimental data. The Standard Linear Solid (SLS) model was fitted to the experimental curves using nonlinear least-squares optimization in Python.

### Features

- Creep test fitting
- Stress relaxation test fitting
- Standard Linear Solid (SLS) constitutive model
- Experimental stress conversion from force measurements
- Nonlinear parameter estimation using SciPy
- Visualization of fitted model responses

### Material Parameters

The fitted parameters are:

- `E1` : Parallel spring elastic modulus
- `E2` : Maxwell spring elastic modulus
- `eta` : Dashpot viscosity coefficient

#### Data Source

The experimental datasets used in this project were obtained as part of coursework conducted in the MechanoBiology and BioMechanics (MBBM) Lab at NJIT.  
The data are shared here solely for educational and academic demonstration purposes related to viscoelastic modeling and parameter fitting.


Please do not reuse or redistribute the experimental data for commercial purposes without permission from the course instructor or laboratory.

### How to Run
1. Clone the repository:
```bash
git clone https://github.com/ZiniaJoti/sls-viscoelastic-model-fitting.git
cd sls-viscoelastic-model-fitting
```

2. Install required packages:

```bash
pip install -r requirements.txt
```
3. Open the notebook:
```bash
jupyter notebook notebooks/project_creep_test.ipynb
```
Run all cells to reproduce the fitted parameters and figures.

The notebook will:

- load the creep and stress relaxation datasets,
- convert force data into stress,
- fit the Standard Linear Solid model,
- generate fitted plots,
- print the fitted material parameters.

### Acknowledgement

This project was completed as part of the Mechanobiology course at NJIT.  
The author would like to thank Professor Farid Alisafaei for his guidance and instruction throughout the course.

Special thanks to Professor Farid Alisafaei's lab: [MechanoBiology and BioMechanics (MBBM) Lab](https://www.mbbm-lab.com/) for providing the experimental setup and laboratory resources used for the creep and stress relaxation experiments.
