# 🌀 Quantum Printing and Light-Driven Vortex Dynamics in Superconductors  

**Author:** Tien-Tien Yeh  
**Affiliations:** Nordita (Stockholm University & KTH Royal Institute of Technology), University of Connecticut  
**Group & PI:** Theoretical Quantum Matter[**Theoretical Quantum Matter**](https://https://tqmatter.org/),  Alexander V. Balatsky
(This README file was prepared with the assistance of ChatGPT, OpenAI.)

---

## 📘 Overview
This repository provides **Jupyter Notebooks** and **Python scripts** used for the simulations and analyses presented in three manuscripts on *structured-light-induced vortex dynamics* and *non-equilibrium superconductivity*.  
All simulations are based on the **time-dependent Ginzburg–Landau (TDGL)** and **generalized TDGL (gTDGL)** formalisms, primarily implemented using [**pyTDGL**](https://github.com/loganbvh/py-tdgl) and our published Github repository [**LG-TDGL**](https://github.com/TienTienYeh/lg-tdgl).

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
- Python ≥ 3.1
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
   ```
2. Create a Python environment and install requirements  
   ```bash
   python -m venv env  
   source env/bin/activate  # on Windows: env\Scripts\activate  
   pip install -r requirements.txt
   ```
3. Launch Jupyter Lab or Notebook and open any file under  
   `/manuscript_I/`, `/manuscript_II/`, or `/manuscript_III/`.

### ▶ Option 2 — Run on Google Colab
Each notebook can be executed directly on Colab:  
1. Open the desired `.ipynb` file on GitHub.  
2. Click **“Open in Colab”** (if enabled) or paste the GitHub URL into [Colab](https://colab.research.google.com).  
3. Mount Google Drive if needed and run the cells sequentially.

---

## 📂 Directory Structure
```
/manuscript_I/      → Jupyter Notebooks for Part I  
/manuscript_II/     → Jupyter Notebooks for Part II  
/manuscript_III/    → Python scripts for Part III  
/videos/            → Generated .mp4 files for Supplementary Materials  
```

---

## 🧭 Citation
If you use or reference these codes, please cite the corresponding manuscripts:  
1. Yeh *T-T et al.*, *Structured light and induced vorticity in superconductors I* ([arXiv:2407.15834](https://arxiv.org/abs/2407.15834))  
2. Yeh *T-T et al.*, *Structured light and induced vorticity in superconductors II* ([arXiv:2412.00935](https://arxiv.org/abs/2412.00935))  
3. Yeh *T-T et al.*, *Light-induced Berezinskii–Kosterlitz–Thouless transition in superconducting films* ([arXiv:2510.22645](https://arxiv.org/abs/2510.22645))

---

## 🧠 Contact
**Tien-Tien Yeh**  
📧 [tien-tien.yeh@uconn.edu](mailto:tien-tien.yeh@uconn.edu)  
🌐 [Google Scholar](https://scholar.google.com/) | [ORCID](https://orcid.org/)

---

*This repository supports open-source reproducibility in the study of structured-light-driven vortex dynamics and non-equilibrium superconductivity.*
