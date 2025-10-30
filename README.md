# 🌀 Quantum Printing and Light-Driven Vortex Dynamics in Superconductors  

**Author:** Tien-Tien Yeh  
**Affiliations:** Nordita (Stockholm University & KTH Royal Institute of Technology), University of Connecticut  
**Collaborators:** Evan Wilson, Mikael Fogelström, Alexander V. Balatsky  

---

## 📘 Overview
This repository provides **Jupyter Notebooks** and **Python scripts** used for the simulations and analyses presented in three manuscripts on *structured-light-induced vortex dynamics* and *non-equilibrium superconductivity*.  
All simulations are based on the **time-dependent Ginzburg–Landau (TDGL)** and **generalized TDGL (gTDGL)** formalisms, primarily implemented using [**pyTDGL**](https://github.com/loganbvh/py-tdgl).

---

## 📗 [Manuscript I — Linearly Polarized Light](/manuscript_I/)
**Title:** *Structured light and induced vorticity in superconductors I: Linearly polarized light*  
**Preprint:** [arXiv:2407.15834](https://arxiv.org/abs/2407.15834)

| File | Description |
|------|-------------|
| `M1fig1a_CoLab_LG_freq.ipynb` | Simulates frequency-dependent light (linear polarization) and snapshots of the order parameter. |
| `M1fig1b_CoLab_LG_imprint.ipynb` | Demonstrates the imprinting effect between optical magnetic field and supercurrent vorticity. |
| `M1fig1c_CoLab_LG_edge.ipynb` | Simulates vortex distributions versus optical spot size. |
| `M1fig2a_CoLab_LG_distribution.ipynb` | Visualizes spatial vortex distributions. |
| `M1fig2b_CoLab_LG_relaxation.ipynb` | Models pulse-laser excitation and order-parameter relaxation. |
| `M1fig2b_CoLab_relaxation_analysis.ipynb` | Analyzes relaxation dynamics. |
| `M1fig6_CoLab_LG_xi.ipynb` | Studies coherence-length-dependent vortex patterns. |
| `M1fig6_Jc.ipynb` | Determines critical current density of the superconducting slab. |
| `M1SI_readH5_M1fig2.ipynb` | Reads `.h5` data and outputs figures for the supplementary video. |

---

## 📘 [Manuscript II — Laguerre-Gaussian Quantum Printing](/manuscript_II/)
**Title:** *Structured light and induced vorticity in superconductors II: Quantum Printing with Laguerre–Gaussian beams*  
**Preprint:** [arXiv:2412.00935](https://arxiv.org/abs/2412.00935)

| File | Description |
|------|-------------|
| `M2fig2a_CoLab_LG_40tau_general.ipynb` | Main simulation of vortex dynamics under Laguerre–Gaussian (LG) illumination; parameters (sample size, optical quantum numbers, field strength) follow the manuscript. |
| `M2fig_CoLab_plot3D_general.ipynb` | Generates 3D vortex-trajectory visualizations from `.h5` data. |
| `M2SI_readH5_general.ipynb` | Reads `.h5` simulation files and produces figures for analysis and supplementary materials. |
| `M2_PNG2video_output_general.ipynb` | Converts sequential `.png` images into `.mp4` videos for Supplementary Materials. |

---

## 📕 [Manuscript III — Light-Induced Berezinskii–Kosterlitz–Thouless Transition](/manuscript_III/)
**Title:** *Light-induced Berezinskii–Kosterlitz–Thouless transition in superconducting films*  
**Preprint:** [arXiv:2510.22645](https://arxiv.org/abs/2510.22645)

| File | Description |
|------|-------------|
| `M3_UConn_arg_6TB.py` | Main simulation combining DC current and circularly polarized optical field on a superconducting slab. |
| `M3_UConn_arg_EkCor.py` | Analyzes kinetic energy and correlation functions. |
| `M3_UConn_arg_SI.py` | Generates supplementary videos from `.h5` simulation results. |
| `M3_PNG2video_output_UConnHCP.py` | Converts `.png` image sequences into `.mp4` videos. |

---

## ⚙️ Dependencies
- Python ≥ 3.9  
- NumPy, SciPy, Matplotlib  
- h5py  
- [pyTDGL](https://github.com/loganbvh/py-tdgl) — L. Bishop-Van Horn *et al.*, *Comput. Phys. Commun.* **291**, 108799 (2023)

---

## 🚀 Getting Started

### ▶ Option 1 — Run Locally
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/quantum-printing-superconductors.git
   cd quantum-printing-superconductors
