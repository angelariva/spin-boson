# Spin-Boson data visualization

The data is produced using Tensor Network Simulations of the Dynamics at Finite Temperature of the Spin-Boson Model for Sub-Ohmic, Ohmic and Super-Ohmic Spectral Density Functions with T-TEDOPA chain mapping [1, 2]. The software is from the Julia package `MPSDynamics.jl`, available [here](https://github.com/angusdunnett/MPSDynamics). The data analysis is in Python.

## Data structure

### Spin-Boson Model
- **spin_boson.ipynb**: the whole data analysis for the Spin-Boson case in one document (updated). The document is too heavy to be rendered on the web browser, the same results are therefore shown in the following notebooks:
  - **correlations.ipynb**: plots of the correlators, of the extended bath occupations, and of the chain occupations;
  - **pops_and_coherences.ipynb**: plots of the populations and coherences, computation of the coherence, relaxation and pure dephasing times;
  - **simulation_specs.ipynb**: plots of the chain coefficients, of the bond dimension evolution, of the spectral density function

### Independent Boson Model
- **indie_boson.ipynb**: the whole data analysis for the IBM, both for the simulated and the analytical results.

### Single Impurity Anderson Model
- **fermions.ipynb**: data analysis for SIAM simulations. The chain mapping used is the one presented in [3].

The pdfs of the plots generated can be found in the directory `plots`.


### References
_____________

[1] A. W. Chin,  ́A. Rivas, S. F. Huelga, and M. B. Plenio. Exact mapping between system-reservoir quantum models and semi-infinite discrete chains using orthogonal polynomials. Journal of Mathematical Physics, 51(9):092109, 2010. arXiv:[1006.4507](https://arxiv.org/abs/1006.4507).

[2] D. Tamascelli, A. Smirne, J. Lim, S. F. Huelga, and M. B. Plenio. Efficient simulation of finite-temperature open quantum systems. Physical Review Letters, 123(9):090402, Aug 2019. arXiv:[1811.12418](https://arxiv.org/abs/1811.12418)

[3] Lucas Kohn and Giuseppe E. Santoro. Efficient mapping for anderson impurity problems with matrix product states. Physical Review B, 104(1):014303, Jul 2021. arXiv:[2012.01424](https://arxiv.org/abs/2012.01424).

[4] Ines de Vega and Mari-Carmen Banuls. Thermofield-based chain mapping approach for open quantum systems. Physical Review A, 92(5):052116, Nov 2015. arXiv:[1504.07228](https://arxiv.org/abs/1504.07228).
