# Spin-Boson data visualization

The data is produced using Tensor Network Simulations of the Dynamics at Finite Temperature of the Spin-Boson Model for Sub-Ohmic, Ohmic and Super-Ohmic Spectral Density Functions with T-TEDOPA chain mapping. The software is from the Julia package `MPSDynamics.jl`, available [here](https://github.com/angusdunnett/MPSDynamics). The data analysis is in Python.

## Data structure

### Spin-Boson Model
- **spin_boson.ipynb**: the whole data analysis for the Spin-Boson case in one document (updated). The document is too heavy to be rendered on the web browser, the same results are therefore shown in the following notebooks:
  - **correlations.ipynb**: plots of the correlators, of the extended bath occupations, and of the chain occupations;
  - **pops_and_coherences.ipynb**: plots of the populations and coherences, computation of the coherence, relaxation and pure dephasing times;
  - **simulation_specs.ipynb**: plots of the chain coefficients, of the bond dimension evolution, of the spectral density function

### Independent Boson Model
- **indie_boson.ipynb**: the whole data analysis for the IBM, both for the simulated and the analytical results.

The pdfs of the plots generated can be found in the directory `plots`.
