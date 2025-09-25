# Axis Model Suite

Reproducible papers and code on fermion structure, gauge completion, and gravity in a scalar–vector field framework.
From six geometric inputs the suite reproduces the full SM fermion spectrum and CKM/PMNS matrices; dynamically
generates the electroweak sector with W/Z masses from a composite orientation scale (v<sub>eff</sub> = Zχ·v); and fixes |Vub|
via a parameter-free rank-2 overlap. The quantum completion is BRST-invariant, anomaly-free, and RG-stable up to the
scalar-coherence cutoff (~10⁵ GeV), consistent with (g-2) and dilepton-compositeness bounds. The gravitational
extension derives the Einstein–Hilbert term at one loop and predicts environment-dependent G(Φ) with lensing/GW
attenuation—providing falsifiable departures from GR.

---

## Contents

- **papers/** — PDFs of the four main works:
  - [*The Axis Model*](The_Axis_Model.pdf) — lays out the foundational postulates of the scalar–vector framework and shows how geometric tri-vector composites reproduce charge, mass, and spin without extra dimensions or hidden particles.  
  - [*A Geometric Origin for the Standard Model Fermion Sector*](A_Geometric_Origin_for_the_Standard_Model_Fermion_Sector.pdf) — derives the full fermion spectrum and CKM/PMNS mixing matrices from just six geometric parameters, achieving sub-percent precision across most observables.  
  - [*Quantum Completion of the Axis Model*](Axis_Model_Quantum_Completion.pdf) — demonstrates that the theory is a consistent EFT: BRST-invariant, anomaly-free, renormalization-stable up to ΛΦ ≈ 10⁵ GeV, and compatible with precision (g-2) and compositeness bounds.  
  - [*Quantum Gravitational Extension of the Axis Model*](Quantum_Gravitational_Extension.pdf) — derives the Einstein–Hilbert term from one-loop dynamics, reinterprets black hole interiors as scalar-incoherent domains, and predicts falsifiable deviations from GR such as environment-dependent G(Φ) and gravitational wave attenuation.  

- **notebooks/** — Interactive notebooks reproducing the analyses from the first three papers.  
Each folder contains the corresponding Colab notebooks; open any `.ipynb` file and click the **“Open in Colab”** badge at the top to launch it live.  
  - [*foundational/*](notebooks/foundational) — *The Axis Model*  
  Benchmarks, stability maps, decay channels, cosmological fits, and gravitational predictions.  
  - [*sm_fermion_sector/*](notebooks/sm_fermion_sector) — *Standard Model Fermion Sector from Internal Tri-Vector Geometry*  
  Fermion spectrum fits, CKM/PMNS mixing, and sensitivity tables.  
  - [*quantum_completion/*](notebooks/quantum_completion) — *Quantum Completion of the Axis Model*  
  Renormalization-group flows, anomaly cancellation checks, and BRST consistency.  
  - *Quantum Gravitational Extension of the Axis Model* — analytic derivations only (no companion notebooks).  

- **data/** — Reference datasets used in the foundational analyses. Each file is either stored here directly (if small) or linked via DOI in the `data/README.md` for reproducibility.
  - *NOνA Posterior Histogram* — Conditional posterior for sin<sup>2</sup>(Φ<sub>23</sub>) in the normal hierarchy, extracted from the NOνA public release. 
    
    -- File: [`posteriors_worc_indep-ord-marg.root`](data/posteriors_worc_indep-ord-marg.root)  
    -- DOI: [10.5281/zenodo.15786985](https://doi.org/10.5281/zenodo.15786985) 
  - *Planck 2018 + CAMB CMB Spectra* —  Used for the log-space suppression fit described in Appendix AG. Compatible with the accompanying Colab notebook.
 
    • [`COM_PowerSpect_CMB-TT-full_R3.01.txt`](data/COM_PowerSpect_CMB-TT-full_R3.01.txt): Planck 2018 TT angular power spectrum.  
    • [`camb_44255652_scalcls_dat.txt`](data/camb_44255652_scalcls_dat.txt): CAMB-generated best-fit ΛCDM spectrum.
    
     -- DOI: [10.5281/zenodo.15770241](https://doi.org/10.5281/zenodo.15770241)
  - *SDSS DR17 Galaxy Velocity Dispersion Sample* — Galaxy velocity dispersion sample from SDSS DR17, used for large-scale structure and dispersion analyses.
      
      -- File: [Skyserver_SQL9_15_2024_12_45_41_AM.csv](data/Skyserver_SQL9_15_2024%2012_45_41%20AM.csv).  
      -- DOI: [10.5281/zenodo.15768686](https://doi.org/10.5281/zenodo.15768686)
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
