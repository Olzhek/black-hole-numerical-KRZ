# Numerical Black Hole Metric Parameter Computation

This repository contains a Jupyter Notebook for computing parameters for numerical black hole metrics using the KRZ framework with Padé approximants.

## Contents

- `KRZ_numerical_parametrization.ipynb`: Main notebook that loads the metric grid, computes Padé coefficients, solves for auxiliary parameters, and handles numerical stability.
- `requirements.txt`: Lists Python dependencies.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Olzhek/black-hole-numerical-KRZ.git
cd black-hole-metric-fitting
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the notebook
```bash
jupyter notebook
```

## License

This code is provided for academic use in connection with the publication:

Mukazhanov, O., Roy, R., Mirzaev T., Bambi, C. "Numerical parametrization of stationary axisymmetric black holes in a theory agnostic framework." *Phys. Rev. D* 110, 024060 (https://doi.org/10.1103/PhysRevD.110.024060)

Please contact the author(s) for permission before reuse or redistribution.
