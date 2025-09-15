# Axis Model Suite

Reproducible papers and code on fermion structure, gauge completion, and gravity in a scalar–vector field framework.
From six geometric inputs the suite reproduces the full SM fermion spectrum and CKM/PMNS matrices; dynamically
generates the electroweak sector with W/Z masses from a composite orientation scale (v_eff = Zχ·v); and fixes |Vub|
via a parameter-free rank-2 overlap. The quantum completion is BRST-invariant, anomaly-free, and RG-stable up to the
scalar-coherence cutoff (~10^5 GeV), consistent with (g-2) and dilepton-compositeness bounds. The gravitational
extension derives the Einstein–Hilbert term at one loop and predicts environment-dependent G(Φ) with lensing/GW
attenuation—providing falsifiable departures from GR.

---

## Contents

- **papers/** — PDFs of the four main works:
  - [*The Axis Model*](The_Axis_Model.pdf) — lays out the foundational postulates of the scalar–vector framework and shows how geometric tri-vector composites reproduce charge, mass, and spin without extra dimensions or hidden particles.  
  - [*Standard Model Fermion Sector from Internal Tri-Vector Geometry*](The_Standard_Model_Fermion_Sector.pdf) — derives the full fermion spectrum and CKM/PMNS mixing matrices from just six geometric parameters, achieving sub-percent precision across most observables.  
  - [*Quantum Completion of the Axis Model*](Axis_Model_Quantum_Completion.pdf) — demonstrates that the theory is a consistent EFT: BRST-invariant, anomaly-free, renormalization-stable up to ΛΦ ≈ 10⁵ GeV, and compatible with precision (g-2) and compositeness bounds.  
  - [*Quantum Gravitational Extension of the Axis Model*](Quantum_Gravitational_Extension.pdf) — derives the Einstein–Hilbert term from one-loop dynamics, reinterprets black hole interiors as scalar-incoherent domains, and predicts falsifiable deviations from GR such as environment-dependent G(Φ) and gravitational wave attenuation.  

- **notebooks/** — Colab notebooks used in the analyses, reproducing key results (fermion mass fits, RG flows, gravitational predictions, etc.).

---

## Getting Started

You can run the notebooks in two ways:

**Option 1: Open in Google Colab (recommended)**  
Click the Colab badge next to a notebook in the [Notebooks](#notebooks) section to launch it directly in your browser — no installation needed.

**Option 2: Run locally with Jupyter**  
Clone the repo and open the notebooks with Jupyter:

    git clone https://github.com/mortonsguide/axis-model-suite.git
    cd axis-model-suite/notebooks
    jupyter notebook

**Dependencies (for local use):** Python ≥ 3.9, NumPy, SciPy, Matplotlib, SymPy, Jupyter.

---

## Citation

If you use this work, please cite the relevant Zenodo record(s):

- *The Axis Model* — https://doi.org/10.5281/zenodo.16164597  
- *Standard Model Fermion Sector from Internal Tri-Vector Geometry* — https://doi.org/10.5281/zenodo.16447452  
- *Quantum Completion of the Axis Model* — https://doi.org/10.5281/zenodo.16489361  
- *Quantum Gravitational Extension of the Axis Model* — https://doi.org/10.5281/zenodo.16500059  

BibTeX entries can be generated directly from each DOI page.

---

## License

This project is released under the MIT License.  
You are free to use, adapt, and redistribute with attribution. See [LICENSE](LICENSE) for details.
