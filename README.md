# Simulating neutrino oscillations on a superconducting qutrit
Notebooks and data of the paper titled "Simulating neutrino oscillations on a superconducting qutrit"
- Cite as
  @article{PhysRevD.108.023013, 
  title = {Simulating neutrino oscillations on a superconducting qutrit},
  author = {Nguyen, Ha C. and Bach, Bao G. and Nguyen, Tien D. and Tran, Duc M. and Nguyen, Duy V. and Nguyen, Hung Q.},
  journal = {Phys. Rev. D},
  volume = {108},
  issue = {2},
  pages = {023013},
  numpages = {13},
  year = {2023},
  month = {Jul},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevD.108.023013},
  url = {https://link.aps.org/doi/10.1103/PhysRevD.108.023013}
}
- The notebooks were run on the IBM quantum computer codename 'ibmq_jakarta'
## Qutrit tuning and neutrino oscillation simulation notebooks
Notebooks are in folder Notebooks.
### Qutrit tuning:
- Assessing high energy level: (Fig 2a, Fig 2d)
[Anharmonicity_and_Rabi_12.ipynb](https://github.com/hanoipho997/Simulating-neutrino-oscillations-on-a-superconducting-qutrit/blob/main/Notebooks/Anharmonicity_and_Rabi_12.ipynb) yields the anharmonicty and pi pulse at subspace 12.
Also, the default IBM default qutrit readout is shown. 
- Measurement pulse optimization: (Fig 2b)
The measurement protocol optimization is shown in [Readout_measurement_optimization_for_qutrit.ipynb](https://github.com/hanoipho997/Simulating-neutrino-oscillations-on-a-superconducting-qutrit/blob/main/Notebooks/Readout_measurement_optimization_for_qutrit.ipynb) where the silhouette map is shown
### Neutrino oscillation simulation:
- Neutrino oscillations in vacuum (Fig 3)
[Simulating_neutrino_oscillations_in_vacuum-ver2.ipynb](https://github.com/hanoipho997/Simulating-neutrino-oscillations-on-a-superconducting-qutrit/blob/main/Notebooks/Simulating_neutrino_oscillations_in_vacuum-ver2.ipynb)
- Neutrino oscillation in matter (Fig 4)
[Simulating_neutrino_in_matter_ver2.ipynb](https://github.com/hanoipho997/Simulating-neutrino-oscillations-on-a-superconducting-qutrit/blob/main/Notebooks/Simulating_neutrino_in_matter_ver2.ipynb)
- Neutrino oscillation with CP violation (Fig 5)
[Simulating_neutrino_oscillations_with_CP_violation_ver2.ipynb](https://github.com/hanoipho997/Simulating-neutrino-oscillations-on-a-superconducting-qutrit/blob/main/Notebooks/Simulating_neutrino_oscillations_with_CP_violation_ver2.ipynb)
## Data: In folder Data 
- Corresponding to notebooks in folder Notebooks
- Data for coherent and incoherent errors is (by repetition experiement) is fig2e_repeat_xp12_addmod.txt
## Note: See branch old-folder to see the previous version of the notebooks
