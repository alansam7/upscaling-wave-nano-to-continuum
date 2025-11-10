# upscaling-wave-nano-to-continuum
# Data and Simulation Scripts

This repository contains the input files, representative system configurations, and analysis codes supporting the study:

> **“Acoustic Response of Molecular Adsorption and Sound Propagation in Nanoporous Materials.”**

The work combines molecular simulations and chemo-poroelastic theory to bridge nanoscale structure–transport coupling in zeolitic materials.

---

## 📂 Repository Contents

### 🔸 LAMMPS Input Files
These files define representative simulation systems used in the study.

| File | Description |
|------|--------------|
| `flow.lmp` | LAMMPS input script for non-equilibrium molecular dynamics (NEMD) simulations of fluid flow through nanoporous channels. |
| `tensile_test.lmp` | LAMMPS input for uniaxial tensile deformation simulations to extract elastic moduli of the solid matrix. |
| `gcmc_zeo.lmp` | Input script for hybrid GCMC–MD simulations of gas adsorption in zeolite frameworks. |
| `system_gcmc.lmpsys` | System configuration file defining atomic positions, types, and topology for GCMC initialization. |

### 🔸 MATLAB Codes
| File | Description |
|------|--------------|
| `Matlab_Codes.rar` | Compressed folder containing MATLAB post-processing scripts for: <br>• Calculating dispersion relations and complex wave numbers <br>• Evaluating poroelastic parameters <br>• Visualizing frequency-dependent acoustic response |

---

## 🧰 Software Requirements

- **LAMMPS** (version ≥ 3Mar2020)
- **MATLAB** (R2021a or later)
- **Python 3.9+** (optional, for auxiliary analysis)
- Recommended libraries: `numpy`, `matplotlib`, `scipy`

---

## 🧪 How to Use

1. Run the `.lmp` files in LAMMPS to reproduce representative simulations.
2. Post-process the output trajectories using the MATLAB scripts in `Matlab_Codes.rar`.
3. Combine molecular results with the continuum-scale chemo-poroelastic analysis as detailed in the manuscript and supplementary information.

---

--

## 📬 Contact
**Corresponding author:**  
Dr. Alan Sam  
Department of Chemical Engineering, Massachusetts Institute of Technology (MIT)  
📧 [alansam@mit.edu](mailto:alansam@mit.edu)

---


